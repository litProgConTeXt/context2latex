# Document typesetting requirements

1. Diagrams.

   - Categorical
   - Petri Nets
   - Event Nets

  TikZ can be externalized see: [tikz picture inside main code or include tikz
  output](https://tex.stackexchange.com/a/234903)

2. Literate Programming structures.

   - Coloured code snippets with line numbers for various programming languages,
     including:

     - ANSI-C
     - Z3/Frama-C
     - JoyLoL

  (could be done with something like [Building a Julia Weave
  document](https://github.com/James-Yu/LaTeX-Workshop/wiki/Compile#building-a-jnw-file))

  Essentially we would build our own weave program by using comment-like
  begin/end environments named for each code class, and then parsing the LaTeX
  to extract out the code chunks.... running pygments over the code and then
  reinputing the resulting latex. This could all be automated using nija or
  latexmk.

  We would probably use `@unified-latex/unified-latex-util-parse` (javascript)
  to do the parsing into an AST which we then walk over.

3. Mathematical Proof theory

  - various formal proof structures:
    - [ebproof](https://www.ctan.org/pkg/ebproof)
    - [bussproofs](https://www.ctan.org/pkg/bussproofs)

4. External hyper-refernces to (multiple drafts of) online versions of our
   documents (complete with comments).

5. Indexing, Glosary and drafts. We need the ability to expose the internal
   index and glosary items across all of our work (including previous drafts) so
   that we can build a central web-accessible index/glosary/drafts.

   (Writeout in ndJson or other format? Easiest if we use luatex....)

6. (Large) Multi-file documents typeset in parallel(?)

7. Conversion to an all commands in a single file of LaTeX for submission to a
   journal.

8. Reference extraction... into bibtex-like files

## Nice to have

1. Document structure in the VSCode tool

2. Problems in the VSCode tool

3. snippets

4. "hacking" LaTeX TextMate Grammar to *add* our own scopes. 

    LaTeX-workshop already has tools to "hack" the grammars and embedded
    languages.

    All LaTeX-workshop grammars are in the JSON format... so *could* be
    programmatically "altered".
