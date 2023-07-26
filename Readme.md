# Inline Literate Programming in LaTeX documents

A tool to "inline" Literate Programming in LaTeX documents

For the Literate Programming in LaTeX projects, we use LaTeX and develop a
lpil-tool (Literate Programming in LaTeXt tool).

This repository (at least initially) explores this approach.

To do this we need to explore:

1. Our ultimate document typesetting requirments.

2. The (allowed) LaTeX packages which can fulfil these requirements.

3. The complexity of parsing LaTeX (to provide a lpil-tool)

This overall analysis can be found in the `docs` folder.

## Reasons

1. The document authouring tools for LaTeX are far more advanced.

  - in VSCode, the LaTeX-Workshop provides many (additional) capabilities which
    would be hard to reproduce. SO which of these capablities are really
    required, and which are simply "nice to have"?

2.

## Problems / Benefits

### LaTeX

1. **CON** LaTeX is a rather baroque "language" depending upon a large number of
   interacting packages (not all of which "play nicely" between themselves).

2. **PRO** LaTeX has a much deeper collection of documentation and tools.

3. **PRO** (sort of) Most Mathematical and Computer Science journals accept
   submissions in "LaTeX" (with heavy qualifications of the range of external
   packages which can be used).
