# TME_Audio_Super-Resolution_Samples
Audio samples for the paper 'Phase-aware music super-resolution using generative adversarial networks'



#### Ground_Truth_HR: high-resolution (HR) audio 
#### Ground_Truth_LR: a low-resolution (LR) input audio
#### F-DNN:  Fully-connected network implementation in the frequency domain 
#### T-CNN: CNN implementation in the time domain
#### F-CNN: CNN (generator network of GAN) implementation in the frequency domain 
#### Proposed: GAN implementation in the frequency domain for HB magnitude estimation and MelGAN implementation for HB phase estimation.


## Phase Estimation methods
#### flip:  the high-frequency phase is produced by flipping the phase of LFC (low frequency components) and adding a negative sign
#### gla: a modified version of GLA is used to maintain both the magnitudes and phase of LFC through the iteration process
#### melgan: HFC (high frequency components) phase is extracted and complemented by the give magnitudes as well as LFC information in order to obtain the final HR output
