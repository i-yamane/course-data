# course-data

Data files used by my courses. Large files are attached to GitHub releases; small
ones are stored in the repository.

## deep-learning

Deep learning course at ENSAI.

### GloVe 6B, 50d (release `glove-6B-50d`)

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

### TP2-1: example image (`deep-learning/tp2-1/cat.jpg`)

- Direct download: <https://raw.githubusercontent.com/i-yamane/course-data/main/deep-learning/tp2-1/cat.jpg>
- 1280 x 960 RGB JPEG.

Photo: ["Domestic cat (Felis catus) - short-haired bicolor"](https://commons.wikimedia.org/wiki/File:Domestic_cat_(Felis_catus)_-_short-haired_bicolor.png)
by Hayden Soloviev, licensed under
[CC BY 4.0](https://creativecommons.org/licenses/by/4.0/), via Wikimedia Commons.
Changes: cropped to 4:3, resized to 1280 x 960 and saved as JPEG.
