# Franklin.jl Support for Visual Studio Code

This extension is intended to provide syntax highlight and code snippets for Franklin.jl markdown files, since vscode/markdown-math does not provide sintax highlighting for specific Franklin ways to enter math-mode 

## Features

The only current feature is syntax highlight for math-mode when entered via \begin{equation|align|...}

This motivated me enought to make this extension, as using \begin{equation*} broke the syntax highlighting, and \nonumber{$$ $$} pollutes the code

## Requirements

You must have the built-in vscode/markdown-math extension enabled. (It is enabled by default)

## Future features:
* Enable the markdown preview button to run Franklin and show the current file.
* Add snippets for setting page variables, start equations, fill page titles and more
* Run Julia code directly from code cells

If you want to contribute, I'm happy to accept pull requests. 

