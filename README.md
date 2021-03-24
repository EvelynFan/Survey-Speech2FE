# Survey-Speech2FE

## 3D

- (SIGGRAPH2017) Audio-Driven Facial Animation by Joint End-to-End Learning of Pose
and Emotion [[Paper](https://users.aalto.fi/~laines9/publications/karras2017siggraph_paper.pdf)][[Demo](https://www.youtube.com/watch?v=lDzrfdpGqw4)]

  :white_small_square: The network learns a mapping from input waveforms to the 3D vertex coordinates of
a face model, and simultaneously discovers a latent code that disambiguates the variations in facial expression that cannot be explained by the audio alone.

<p align="center"><img width="60%" src="imgs/Siggraph17.png"/></p>

- (SIGGRAPH2017) Synthesizing Obama: Learning Lip Sync from Audio [[Paper](https://grail.cs.washington.edu/projects/AudioToObama/siggraph17_obama.pdf)][[Demo](https://www.youtube.com/watch?v=9Yq67CjDqvw)]

  :white_small_square: It synthesizes only the region around the mouth and borrow the rest of Obama from a target video. The system first converts audio to the sparse mouth shape, then generates photo-realistic mouth texture, and finally composites it into the mouth region of a target video. 

## 2D

- (ACM MM2020) Talking Face Generation with Expression-Tailored Generative
Adversarial Network [[Paper](https://dl.acm.org/doi/abs/10.1145/3394171.3413844)] 

  :white_small_square:It uses an expression encoder to disentangle the emotion information from expressional video clips, thus generating high quality expression-tailored face videos beyond audio-lip
synchronization.

<p align="center"><img width="40%" src="imgs/ET-GAN.png"/></p>