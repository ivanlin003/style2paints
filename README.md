# Welcome to STYLE2PAINTS 2.1 !

**First of all, why not spend 5 minutes to try it yourself!**

[WebAPP: PaintsTransfer](http://paintstransfer.com)

The AI can paint on a sketch according to a given specific color style.

The AI can create its own color style to paint on a sketch.

The AI can transfer illustrations' style.

# Tutorial

[Tutorial001(BiliBili)](https://www.bilibili.com/video/av17537429/)

# Screenshots

![web_preview](https://raw.githubusercontent.com/lllyasviel/style2paints/master/tempfile/001.png)

![web_preview](https://raw.githubusercontent.com/lllyasviel/style2paints/master/tempfile/002.png)

![web_preview](https://raw.githubusercontent.com/lllyasviel/style2paints/master/tempfile/003.png)

![web_preview](https://raw.githubusercontent.com/lllyasviel/style2paints/master/tempfile/011.png)

![web_preview](https://raw.githubusercontent.com/lllyasviel/style2paints/master/tempfile/004.png)

![web_preview](https://raw.githubusercontent.com/lllyasviel/style2paints/master/tempfile/005.png)

![web_preview](https://raw.githubusercontent.com/lllyasviel/style2paints/master/tempfile/006.png)

![web_preview](https://raw.githubusercontent.com/lllyasviel/style2paints/master/tempfile/007.png)

![web_preview](https://raw.githubusercontent.com/lllyasviel/style2paints/master/tempfile/008.png)

![web_preview](https://raw.githubusercontent.com/lllyasviel/style2paints/master/tempfile/009.png)

![web_preview](https://raw.githubusercontent.com/lllyasviel/style2paints/master/tempfile/010.png)

# Launch Server

*you need a python 3.5/3.6 GPU environment with cuda.*

    pip install tensorflow_gpu
    pip install keras
    pip install bottle
    pip install gevent
    pip install h5py
    pip install opencv-python
    pip install scikit-image
    git lfs clone https://github.com/lllyasviel/style2paints.git
    cd style2paints/server
    python server.py

# Models

Models are available via Git-LFS.

Currently, we reserve all rights about all these models. 

# Training Datasets

1. The recommended training dataset of illustrations is the 400k images from [nico-opendata](https://nico-opendata.jp/en/seigadata/index.html)

2. The recommended training sketches is from [sketchKeras](https://github.com/lllyasviel/sketchKeras)

# Community

QQ Group ID: 184467946

## Acknowledgements

Thanks a lot to TaiZan. This project could not be achieved without his great help.
