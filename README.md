# course-data

Data files used by the deep learning course at ENSAI. The files are attached to
GitHub releases, not stored in the repository itself.

## GloVe 6B, 50d

- Release: [`glove-6B-50d`](../../releases/tag/glove-6B-50d)
- File: `glove.6B.50d.txt.gz` (gzip of the original `glove.6B.50d.txt`: 400,000 uncased tokens, 50 dimensions, one token per line followed by its 50 values)
- SHA-256: `12734d03a33d81c3b655726f6373306131974aa38327a21c0157f73b7b6ec918`
- Direct download: <https://github.com/i-yamane/course-data/releases/download/glove-6B-50d/glove.6B.50d.txt.gz>

These are the pre-trained GloVe vectors trained on Wikipedia 2014 + Gigaword 5
(`glove.6B`), from the Stanford NLP group's
[GloVe project page](https://nlp.stanford.edu/projects/glove/), which states that
the pre-trained word vectors are made available under the
[Open Data Commons Public Domain Dedication and License v1.0](http://www.opendatacommons.org/licenses/pddl/1.0/).
Only the 50d vectors are redistributed here, to keep downloads small.

Reference: Jeffrey Pennington, Richard Socher, and Christopher D. Manning. 2014.
*GloVe: Global Vectors for Word Representation.* Proceedings of EMNLP 2014.
