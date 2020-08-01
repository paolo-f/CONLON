This folder contains three samples for dataset HP-10:

- One interpolation from two randomly sampled z values obtained from MuseGAN (Dong et al. 2018):

  - [MuseGAN](./MuseGAN_interpolation_from_random_to_random.mp3)

- Two interpolation from two specific start-goal test set patterns obtained from Wasserstein autoencoders:

  - [Patterns described by our CONLON PianoRolls](./WAE_PRC_interpolation_from_HighPop_Bridge_121_to_ProgressiveTrance_Bridge_74.mp3)
  - [Patterns described by PianoRolls as in (Dong et al. 2018)](./WAE_PR_interpolation_from_HighPop_Bridge_121_to_ProgressiveTrance_Bridge_74.mp3)

For all models we set the interpolation length equal to 64 patterns, the desired length equal to 16 patterns, and the widest-path horizon equal to 20 patterns.
