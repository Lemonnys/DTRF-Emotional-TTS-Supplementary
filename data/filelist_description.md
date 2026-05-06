# Filelist Description

The emotion-control filelists are constructed from the English subset of ESD.

The four non-neutral emotion categories used for emotion-control training and evaluation are:
- Angry
- Sad
- Happy
- Surprise

Neutral utterances are used for neutral backbone adaptation and neutral-anchor construction.

The emotion-control evaluation follows a seen-speaker but text-disjoint setting. All 10 English ESD speakers appear in the training, validation, and test partitions, while evaluation utterances and transcripts are disjoint from the training data whenever applicable.

The split statistics are:

| Split | Speakers | Utterances | Emotions | Unique texts |
|---|---:|---:|---:|---:|
| Train | 10 | 13,300 | 4 | 480 |
| Validation | 10 | 200 | 4 | 157 |
| Test | 10 | 500 | 4 | 284 |