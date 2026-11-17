# Project structure
Each project should follow the same structure, as far as possible.
```fish
    ProjectDir/
        |- src/
        |   |- ProjectMain.tex
        |   |- ProjectMain.pdf
        |   |- sectioning/
        |- extra/
            |- BibTeX/
            |- preamble.tex
```

## Class, packages and commands 
Each project should use the `llncs` class, which is provided by default with TexLive.
    As for the packages and commands, these should be put in `preamble.tex` to leave the main tex file clean.
    If a theme should be used, put it in the `extra` directory and add a `\usepackage{theTheme}` in the preamble file.

### BibTeX
Cite each source if possible, whether these are books, papers, or anything else.
