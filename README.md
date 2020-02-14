# SLP
Semantic Label Propagation GUI Application for Interactive Region Annotation (My master's thesis in 2020)

![gif](https://github.com/kuboyoo/SLP/blob/master/assets/demo_SLP.gif)

## Requirements
* g++     (Ubuntu 8.3.0-6ubuntu1~18.10.1) 8.3.0
* OpenCV3 (3.4.6)
* gnuplot (for and plot graph)
* Qt5     (QMake version 3.1 / Qt version 5.11.1) for GUI Application


## Usage
### Linux
```cd src
qmake 
make -j4
./segImg```

### Mac OS
`cd src`
add final line in segImg.pro `QMAKE_MACOSX_DEPLOYMENT_TARGET=10.9`  
```qmake
make -j4
./segImg/Contents/MacOS/segImg```
