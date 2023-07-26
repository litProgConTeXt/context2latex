# Required LaTeX packages 

We use the [LaTeX wiki-book](https://en.wikibooks.org/wiki/LaTeX) as our modern
documentation for the LaTeX document typesetting language.

## Journal requirements

- [Theory and Applications of Categories](http://www.tac.mta.ca/tac/)
  ([requirements](http://www.tac.mta.ca/tac/authinfo.html))

  - One TeX file (all in one format)
  - No external hyper-links
  - Diagrams as eps OR Michael Barr's front-end for XY-pic

- [Association for Computing
  Machinery](https://www.acm.org/publications/journals) ([Journal of the ACM
  requirements](https://dl.acm.org/journal/jacm/manuscripts))

- [American Mathematical Society](https://www.ams.org) ([Journal Author
  Resources](https://www.ams.org/arc/journals/index.html))

- [arXiv](https://arxiv.org/) ([submission
  requirements](https://info.arxiv.org/help/policies/instructions_for_submission.html)
  ([AMS/LaTeX submissions](https://info.arxiv.org/help/submit_tex.html)))

## Diagrams

- Categorical

- General

## Code snipets

In ConTeXt we use the `typing` (`verbatim`-like) environment together with the
`???` for code colouring.

The `typing` enviroment provides off-setting, back-ground control as well as
line numbering of the code.

From the LaTeX book, use either `listings` or `minted`. Unfortunately since
`minted` uses the external (python) `Pygments` package, it will be forbidden by
most Journal author requirements.

## Proof theory


## Index / Glosary

In ConTeXt the cross-references are stored in a fairly accessible Lua formated
"database".


