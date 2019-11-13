Write paper about YYY

Below is a checklist of items.  Each item, when checked, should be accompanied by a comment enumerating your action.

You may find helpful a few online resources:

 * [Ten Simple Rules for Reproducible Computational Research](https://journals.plos.org/ploscompbiol/article?id=10.1371/journal.pcbi.1003285)
 * [Ten Simple Rules for Reproducible Research in Jupyter Notebooks](https://arxiv.org/abs/1810.08055)

Notes on text preparation:

 * Use markdown wherever possible until the last possible moment, then convert to `LaTeX` (if necessary) using `pandoc`
 * Use "semantic" text-wrapping.  This means line breaks at *sentence* end, rather than at fixed character width.  This makes diffing much easier.
 * You do not need to issue pull requests to a paper you are preparing, unless you explicitly need approval or feedback on specific sections.
 * Figures should be in vector format wherever possible without taking too much space.  Prefer SVG for diagrams and non-image plots, and PNG for image plots.  Images should be regeneratable from the command line without re-running considerable amounts of analysis.

 - [ ] Initialize repository (can use template)
   - [ ] Commit *all* preliminary analysis/data collection scripts
   - [ ] Add references to *all* external or collected data
   - [ ] Commit *all* initialization and data cleaning scripts
   - [ ] Commit a [snakemake](https://snakemake.readthedocs.io/en/stable/) file to re-run all analysis
 - [ ] Link your repository *in this repository* under the README.md file.
 - [ ] Initialize your manuscript
   - [ ] Generate blank `.md` file for each top-level section

 - [ ] Generate paper from a *clean* repository (i.e., fresh clone should generate identical outputs)
 - [ ] Write the paper
 - [ ] Include appropriate acknowledgments
   - [ ] Software (if not cited in body of work)
   - [ ] Anyone who provided feedback, formally or informally
   - [ ] Computing resources
   - [ ] Grants that supported the work
   - [ ] Institutions that supported the work
 - [ ] Publish your data
   - [ ] Develop metadata
   - [ ] De-identify (if appropriate)
   - [ ] Identify repository ([figshare](https://figshare.com/), [zenodo](https://zenodo.org/), etc)
   - [ ] Submit to repository
 - [ ] Submit
   - [ ] Submit to journal
   - [ ] Submit to [arXiv](https://arxiv.org/) / [figshare](https://figshare.com/)
   - [ ] Submit to [IDEALS](https://ideals.illinois.edu/)
   - [ ] Add to [DXL repository](https://github.com/data-exp-lab/data-exp-lab.github.io/)
