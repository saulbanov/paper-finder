# Free Paper Finder

A single static page: paste DOIs, get the free legal copies of each paper (PubMed Central, open-access publisher
versions, repository copies, preprints), or the corresponding author to ask when there is none.

Your browser queries OpenAlex, Europe PMC and Crossref directly; arXiv DOIs link straight to arXiv. No server, no
keys, nothing stored. Links: `#10.1126/science.1235009` or `?doi=...` open a lookup directly.

The full pipeline (download, parse, funding and conflict flags, dossier drafts) is the private paper-scraper repo;
each result shows its `papers.py get` command.
