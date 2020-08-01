## CONLON MIDI music generator

CONLON is a pattern-based MIDI music generator with three main features:
- A novel pianoroll-like description of patterns
- Wasserstein eutoencoders as the underlying generative model
- Optimal trajectories for interpolation and swirls.

CONLON was developed as a collaborative effort between the [AI Lab](https://ai.dinfo.unifi.it) at [DINFO](https://dinfo.unifi.it), [University of Florence](https://www.unifi.it), (Italy) and [MUSI-CO](https://www.musi-co.com/), a music generation startup based in Eindhoven (the Netherlands).

This page contains additional information and data for the paper

L. Angioloni, T. Borghuis, L. Brusci, and P. Frasconi. CONLON: A Pseudo-Song Generator Based on a New Pianoroll, Wasserstein Autoencoders, and Optimal Interpolations. __In  Proceedings of the 21st International Society for Music Information Retrieval Conference__, ISMIR 2020.

## Dataset
The paper comes with two novel datasets especially composed by professional musicians for this research. Datasets are made available here **exclusively for academic research purposes** and cannot be used in any commercial project.

### ASF-4
This is a dataset in genres __Acid Jazz__, __Soul__, and __Funk__. It consists of 910 patterns of four 4/4 bars each, with four instruments: Drums, Bass, Rhodes piano, Hammond organ. [Download MIDI files](./ASF-4.tgz)

### HP-10
This is a dataset in genres __High Pop__ and __Progressive Trance__. It consists of 983 patterns of four 4/4 bars each, with ten instruments: drums, bass,
Rhodes, brass-synth, choir, dark-pad, guitar, lead, pad, and strings. [Download MIDI files](./HP-10.tgz)

## Source code
We are sorry that source code cannot be provided at this time. The [WAE implementation of Ilya Tolstikhin](https://github.com/tolstikhin/wae) is a good starting point for developing the generator.

## Archtecture details

We provide here a Keras `model.summary()` for the architectures used in the paper.
