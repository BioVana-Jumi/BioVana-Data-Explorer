# BioVana Data Explorer

A static, filterable explorer for **synthetic** BioVana datasets (BioAtlas, PROS and ACENTDFB studies). All records are generated from the aggregate structure of the source data; none describes a real participant or sample. For demonstration only, not for analysis.

- `index.html`: the explorer (no build step)
- `data.json`: the synthetic data the page loads

Host as static files (Vercel, GitHub Pages, Netlify). Keep both files in the same folder.

Notes on ACENTDFB: records were generated from a sample summary table (nature of study, sample type, target organism, number of samples) and contain only those variables. Disease category is inferred from the target organism, and DNA and cDNA are marked as derived samples.
