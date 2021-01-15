# news_tonality_with_uuusa

2-steps pipeline for calculating news tonality:

1. Get universal dependencies (form conll files) using [stanza](https://stanfordnlp.github.io/stanza/#getting-started) library.
2. Feed conll files to [uuusa](https://github.com/aghie/uuusa) model
