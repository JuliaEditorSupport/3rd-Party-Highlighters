# 3rd-Party-Highlighers and other editors with Julia support
This repo is to track the various highlighers for julia or text editor with native Julia support that exist as parts of other repositories.


Use issues in this repository to keep track of issues in other repositories that provide syntax highlighting for julia.
This repo is not for tracking highlighers that are in software solely used by julia users (Eg the packages in JuliaEditorSupport),
but rather in things like:

## 3rd-Party-Highlighers

 - highlight.js -- [julia](https://github.com/highlightjs/highlight.js/blob/11.11.1/src/languages/julia.js) and [julia-REPL](https://github.com/highlightjs/highlight.js/blob/11.11.1/src/languages/julia-repl.js), which does Discourse.
 - [CodeMirror](https://github.com/codemirror/codemirror5/blob/5.65.19/mode/julia/julia.js), which highlights Jupyter notebooks
 - [Pygments](https://github.com/pygments/pygments/blob/2.19.2/pygments/lexers/julia.py)
 - [Rouge](https://github.com/rouge-ruby/rouge/blob/v4.5.2/lib/rouge/lexers/julia.rb)
 - [Prism](https://github.com/PrismJS/prism/blob/v2/src/languages/julia.ts)

## Other text editors
Some text editors ([not listed here](https://github.com/JuliaEditorSupport)) provides natively Julia support:

 - [micro](https://github.com/zyedidia/micro/blob/v2.0.14/runtime/syntax/julia.yaml)

## Note
Let us know if you are aware of more tools that we should be tracking.

Basically if it is a tool and you can't work out why it is not highlighting correctly, please raise an issue here.

Basically, if the support for julia is a couple of files in repository that servers many languages then tracking deficiencies in those tools is what we want to do here.
Thus providing better visibility to the julia community, particularly around times of a new release.

