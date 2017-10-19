# 版本说明

###1 版本构成

- 基于ORB_SLAM2[原版](https://github.com/raulmur/ORB_SLAM2)以及[fschopp的分支](https://github.com/fschopp/ORB_SLAM2)改造而来
- fschopp分支解决了OSX的一些代码兼容问题，以及Pangolin调用问题（必须主线程运行），但是由于内置了Opencv2.4.13，在最新的OSX下不兼容
- 从原版中将build.sh,build_ros.sh拷贝过来，将cmake_modules文件夹以及CMakeLists.txt文件拷贝过来替换原有文件夹以及文件。之后按照原版的方式进行编译。
- 编译过程中会遇到一些问题，google即可解决。



###2 版本特点

- 兼容OSX 10.12，10.13, 采用Clang编译器，兼容LLVM8.0、9.0
- Pangolin可以运行，看实时效果。但按钮尺寸不正常（基本不影响）。
- 基于OpenCV 3.3.0
- 所有依赖库需要自行按照原版的提示依次安装，可用HomeBrew，最新版即可。









