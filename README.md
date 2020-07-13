# ECE657-Project
**Podcasts Deepfake Audio with Multilingual**

Abstract
In this realm of media content consumption, podcasts play a prominent role in its exponential
growth. So, we thought that the same podcasts content should be reachable to all diversities of
people with their favorite “artistic voice and language”, irrespective of which voice the original
content is delivered. To achieve this with robust and reliability, Convolutional Neural Networks,
NLP and GAN’s are key building blocks of our model. There are three key stages involved, first
the raw audio to text conversion, second language modelling and third inversion back to audio.
As this case is speech, mel-spectogram and aligned linguistic features are the intermediate
representations with phoneme boundaries.
In this project, we will be considering the publicly available podcasts dataset for initial process to
generate the text data and perform sequence to sequence modelling with 4 different languages.
The obtained data will be given to a feed-forward convolutional architecture to generate the
audio waveform in GAN setup. For speech synthesis we will be initially training the CNN with
open voice datasets of any famous person and evaluate the metric with Mean Opinion Score
(MOS). We will consider the traditional speech synthesis architectures such as Google Wavenet,
DeepVoice2 for our architecture design and parameters.
