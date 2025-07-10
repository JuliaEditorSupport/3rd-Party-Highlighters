# 3rd-Party-Highlighters and other editors with Julia support

This repo tracks various syntax highlighters and text editors with Julia support that are maintained outside the [JuliaEditorSupport](https://github.com/JuliaEditorSupport) organization.

## Parsers

- [tree-sitter-julia](https://github.com/tree-sitter/tree-sitter-julia/),
  used by:
  - Neovim (since v0.5, requires [nvim-treesitter](https://github.com/nvim-treesitter/nvim-treesitter) to install)
  - Emacs (since 29.1, requires [julia-ts-mode](https://github.com/JuliaEditorSupport/julia-ts-mode))
  - Helix
  - Zed
- [lezer-julia](https://github.com/JuliaPluto/lezer-julia),
  used by CodeMirror6-based editors, including Pluto.jl.
  - Note that Jupyter uses CodeMirror6, but Julia support still uses the legacy [CodeMirror 5 mode](https://github.com/codemirror/codemirror5/blob/5.65.19/mode/julia/julia.js).

## Regex-based scanners

- Highlight.js (
  [julia](https://github.com/highlightjs/highlight.js/blob/11-stable/src/languages/julia.js) and
  [julia-repl](https://github.com/highlightjs/highlight.js/blob/11-stable/src/languages/julia-repl.js)
  ), used by:
  - Julia Discourse
  - Stack Overflow
- [VSCode / TextMate](https://github.com/julia-vscode/julia-vscode/blob/main/syntaxes/julia_vscode.json)
- [Micro editor](https://github.com/zyedidia/micro/blob/v2.0.14/runtime/syntax/julia.yaml)
- [Prism](https://github.com/PrismJS/prism/blob/v2/src/languages/julia.ts)
- [Pygments](https://github.com/pygments/pygments/blob/2.19.2/pygments/lexers/julia.py)
- [Rouge](https://github.com/rouge-ruby/rouge/blob/v4.5.2/lib/rouge/lexers/julia.rb)


## Note

Use issues in this repository to keep track of issues in other repositories that provide syntax highlighting for julia.

Let us know if you are aware of more tools that we should be tracking.

Basically if it is a tool and you can't work out why it is not highlighting correctly, please raise an issue here.

Basically, if the support for julia is a couple of files in repository that servers many languages then tracking deficiencies in those tools is what we want to do here.
Thus providing better visibility to the julia community, particularly around times of a new release.

