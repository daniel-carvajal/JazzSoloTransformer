# JazzSoloTransformer

Transformer built with Pytorch that generates MIDI files of jazz piano solos.

This Relative Attention Transformer is based on the paper [Music Transformer](https://arxiv.org/abs/1809.04281) and was trained on the Weimar Jazz Database [(WJazzD)](https://jazzomat.hfm-weimar.de/dbformat/dboverview.html). Trained using tools from [music-transformer](https://github.com/spectraldoy/music-transformer). It uses the vocabulary explained in [This Time with Feeling:
Learning Expressive Musical Performance](https://arxiv.org/pdf/1808.03715.pdf). I experimented with various file preprocessing lengths and found 512 to produce reasonable results. Trained for 5 epochs.

The following Audio examples pertains to generated MIDI files by the Transformer. 

### Example 1

https://user-images.githubusercontent.com/40804574/217735179-9b6df759-b72d-43ee-8ef7-0c0bad68e94b.mp4


### Example 2

https://user-images.githubusercontent.com/40804574/217735361-ebedd14b-f019-40ac-8216-f96c9decd354.mp4


### Example 3

https://user-images.githubusercontent.com/40804574/217735375-80c7aee6-f938-4799-a74a-ff0444ba0c2e.mp4


