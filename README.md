# 3rd-Party-Highlighers and other editors with Julia support
This repo is to track the various highlighers for julia or text editor with native Julia support that exist as parts of other repositories.


Use issues in this repository to keep track of issues in other repositories that provide syntax highlighting for julia.
This repo is not for tracking highlighers that are in software solely used by julia users (Eg the packages in JuliaEditorSupport),
but rather in things like:

## 3rd-Party-Highlighers

 - highlight.js -- [julia](https://github.com/isagalaev/highlight.js/blob/861140d74522d6d50401ef8037f0ec1130954a8f/src/languages/julia.js) and [julia-REPL](https://github.com/isagalaev/highlight.js/blob/861140d74522d6d50401ef8037f0ec1130954a8f/src/languages/julia-repl.js), which does Discourse.
 - [CodeMirror](https://github.com/codemirror/CodeMirror/blob/3d89b71b955b72e61430f7f38e2350489cad9e15/mode/julia/julia.js), which highlights Jupyter notebooks
 - [Pygments](https://bitbucket.org/birkenfeld/pygments-main/src/7941677dc77d4f2bf0bbd6140ade85a9454b8b80/pygments/lexers/julia.py)
 - [Rouge](https://github.com/jneen/rouge/blob/b8a2c9df24817b28303f9aad449524fdd7261416/lib/rouge/lexers/julia.rb)
 - [Prism](https://github.com/PrismJS/prism/blob/22cb0187331d9e7239b23431178981bdcc8e1064/components/prism-julia.js)
 - [Google Prettify](https://github.com/google/code-prettify), which highlights Stack Overflow

## Other text editors
Some text editors ([not listed here](https://github.com/JuliaEditorSupport)) provides natively Julia support:

 - [micro](https://github.com/zyedidia/micro)

## Note
Let us know if you are aware of more tools that we should be tracking.

Basically if it is a tool and you can't work out why it is not highlighting correctly, please raise an issue here.

Basically, if the support for julia is a couple of files in repository that servers many languages then tracking deficiencies in those tools is what we want to do here.
Thus providing better visibility to the julia community, particularly around times of a new release.

