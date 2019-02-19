# style_transfer

### This is a keras implementation of Style Transfer of images.
### It takes in a list of frames extracted from a video and applies style transfer to it based on the style images provided.
### style_transfer_keras.ipynb is the jupyter notebook which consists of the code to transfer the styles of the frames of the video.

## Requirements
1. keras (and associated dependencies)
2. numpy, scipy
3. Python 3
4. Pillow

## Losses taken into account:
1. Style loss
2. Content loss
3. Total variation loss
4. Stabilization loss



#### References:
[1] Ruder et al. 2016. Artistic Style Transfer for Videos. https://github.com/manuelruder/artistic-videos<br />
[2] Gatys et al. 2015. A Neural Algorithm of Artistic Style<br />
[3] Stabilizing neural style-transfer for video. Jeffrey Rainy and Archy de Berker.  https://medium.com/element-ai-research-lab/stabilizing-neural-style-transfer-for-video-62675e203e42<br />
[4] https://github.com/kangeunsu/ArtML/tree/master/fast-style-transfer<br />
[5] https://github.com/titu1994/Neural-Style-Transfer<br />
[6] https://github.com/jcjohnson/neural-style <br />
[7] https://github.com/ElementAI/chainer-fast-neuralstyle/blob/stable-style/train.py#L177 <br />

