# Lecture notes on OpenAI results

Course notes for reading groups that study recent mathematical results from OpenAI. Each project is one document for a group's whole run, in chapters by topic. These notes are independent and are not affiliated with OpenAI.

## Projects

| Project | Notes | Contents |
|---|---|---|
| Unique Games | [`ugc/ugc.pdf`](ugc/ugc.pdf), *Lecture Notes on the Unique Games Theorem* | Part I proves the 2-to-2 Games Theorem by OpenAI's method. Part II upgrades the proof to OpenAI's Unique Games Theorem. Part III, which will prove the results that Part II quotes, is in progress. |

## Status of the mathematics

- OpenAI's *The Unique Games Theorem* is an unrefereed preprint (September 23, 2026) whose repository contains a Lean formalization.
- Part I of the Unique Games notes assembles the 2-to-2 proof inside OpenAI's framework. This assembly is new to the notes and has not been refereed.
- The notes were prepared with AI assistance (Claude). Corrections are welcome as GitHub issues.

## Building

Each project builds from its own directory, for example `cd ugc && latexmk -pdf ugc.tex`. The project's `latexmkrc` puts `common/` on the TeX path, and `common/notes.sty` holds the shared preamble.

## License

The notes and their LaTeX sources are licensed under the [Creative Commons Attribution 4.0 International License](LICENSE) (CC BY 4.0). You may share and adapt them with credit to Abhijeet Mulgund.
