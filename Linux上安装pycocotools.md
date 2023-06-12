# Linux上安装pycocotools
*反正我直接pip install pycocotools 不行*
1. 下载仓库`git clone https://github.com/cocodataset/cocoapi.git`或者 https://github.com/cocodataset/cocoapi 自行解决
2. 前置条件，需要安装cython `pip install cython`
3. `cd PythonAPI`
4. `python setup.py build_ext install` *如果报路径不对之类的错误自行调整下*
***
参考贴 https://github.com/matterport/Mask_RCNN/issues/6
