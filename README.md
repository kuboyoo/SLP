# SLP
Semantic Label Propagation GUI Application for Interactive Region Annotation

![gif](https://github.com/kuboyoo/SLP/blob/master/assets/demo_SLP.gif)

## Requirements
* g++     (Ubuntu 8.3.0-6ubuntu1~18.10.1) 8.3.0
* OpenCV3 (3.4.6)
* gnuplot (for and plot graph)
* Qt5     (QMake version 3.1 / Qt version 5.11.1) for GUI Application

## Usage
### Linux
```
cd src
qmake 
make -j4
./segImg
```

### Mac OS
```cd src```
add final line in `segImg.pro`
```
QMAKE_MACOSX_DEPLOYMENT_TARGET=10.9
```
```
qmake
make -j4
./segImg.app/Contents/MacOS/segImg
```

## Lisense
This software includes the work that is distributed in the Apache License 2.0

## Contact
If you want to use this tool, please mail to [kuboyu@mineo.jp](mailto:kuboyu@mineo.jp)
