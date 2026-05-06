# Metric Definitions

## SECS
Speaker Encoder Cosine Similarity. Speaker embeddings are extracted using a WavLM-based speaker verification encoder. Each generated utterance is compared with a neutral reference utterance from the same target speaker.

## SER-UAR
Unweighted average recall computed using an independent WavLM Base Plus SER evaluator trained on real ESD speech from the four non-neutral emotion categories: Angry, Sad, Happy, and Surprise.

## SER-Conf.
Mean posterior probability assigned by the SER evaluator to the target emotion class.

## E2V-CS
Emotion2vec Cosine Similarity between the generated utterance embedding and the corresponding target-emotion anchor. This metric is used as an auxiliary embedding-space diagnostic measure.

## ASR-WER
Word Error Rate computed from Whisper English ASR transcriptions and the reference transcripts.

## NMOS
Naturalness mean opinion score.

## SMOS
Speaker similarity mean opinion score. A neutral reference utterance from the corresponding target speaker is provided during evaluation.

## EMOS
Emotion mean opinion score, measuring perceived target-emotion expressiveness.