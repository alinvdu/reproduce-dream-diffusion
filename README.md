# Reproduce Dream Diffusion
In this repository I reproduced Dream Diffusion paper in Colab environment, pre-trained EEG representation and use author checkpoints to generate images.

EEG pre-trained on 500 epochs: https://drive.google.com/file/d/1G79aAmd2pO4ZPuu9FC6dI_A4gqmAuiJu/view?usp=sharing

EEG data for preprocessing: https://tinyurl.com/eeg-visual-classification -> eeg_5_95_std.pth (use the initial notebook cells to preprocess this file into multiple .npy).

### Promo
Neural art is a dream diffusion implementation which leverages a 14 channels EEG with 1024 time points that can be used to generate art images. Same architecture trained with art images from a midjourney stable diffusion model. Check it out here: https://github.com/alinvdu/neural-art

Some results:

![download](https://github.com/bobergsatoko/reproduce-dream-diffusion/assets/16021447/59a6b9cb-340d-47a3-a30b-dd5ac45e4af7)
![download](https://github.com/bobergsatoko/reproduce-dream-diffusion/assets/16021447/65dfc451-1085-4fbd-a143-eff7a2dfcda3)

Copyright notice:
MIT License

Copyright (c) 2023 bbaaii

Permission is hereby granted, free of charge, to any person obtaining a copy
of this software and associated documentation files (the "Software"), to deal
in the Software without restriction, including without limitation the rights
to use, copy, modify, merge, publish, distribute, sublicense, and/or sell
copies of the Software, and to permit persons to whom the Software is
furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in all
copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR
IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY,
FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE
AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER
LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM,
OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE
SOFTWARE.

Dream Diffusion repo: https://github.com/bbaaii/DreamDiffusion
