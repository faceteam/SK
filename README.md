SK
==

Skills and Knowledges that may or may not be used.

### Programming Language and Tools

- C/C++
  - 数据处理
  - 算法实现及优化
- Python
  - 快速数据处理
  - 数据分析与可视化
  - 算法原型实现
  - 各种日常打杂
- Matlab
  - 数据可视化
  - 算法原型实现
- Git && Github
  - 代码管理与版本控制
  - 代码分享
- CMake
  - C/C++ 代码管理
  - C/C++ 项目跨平台构建与分发

### MOOC

- [Coursera][coursera]
- [Udacity][udacity], 需翻墙
- [Edx][edx], 需翻墙
- [网易公开课][open-163]
- [Machine Learning][ml-ng] by [Andrew Ng][ng]
- [How to Use Git and GitHub][uda-git]
- [Introduction to Computer Vision][uda-cv]
- [抽象编程][sf-ab]

### C/C++

- [isocpp/CppCoreGuidelines](https://github.com/isocpp/CppCoreGuidelines)
- [Google 开源项目风格指南中文版](http://zh-google-styleguide.readthedocs.org/en/latest/contents/)
- [awesome-cpp](https://github.com/fffaraz/awesome-cpp)

### Python

- [The Hitchhiker’s Guide to Python](http://docs.python-guide.org/en/latest/)
- [awesome-python](https://github.com/vinta/awesome-python)

### Regular Expression

- 正则表达式
- **文本处理与信息提取**
- 各种编程语言自身的实现

### Recommended Tools

- 操作系统平台
  - Windows
  - Linux
  - Unix
- 集成开发环境
  - [Visual Studio][vs]
  - [Eclipse][eclipse]
  - [Code Blocks][codeblocks]
  - [PyCharm][pycharm]
- 文本编辑器
  - [Sublime Text][sublime]
  - [Notepad++][notepad++]
- 终端文本编辑器
  - [Vim][vim]
  - [Emacs][emacs]
- 科学计算集成环境
  - [Spyder][spyder]
  - [Matlab][matlab]

### Machine Learning and Data Mining

- [Yoshua Bengio 关于 DL 的书](http://www.iro.umontreal.ca/~bengioy/dlbook/)
  - 线性代数与概率论基础
  - ML 理论基础
  - DL 理论基础
  - 前沿性模型分析
- [好东西论坛](http://memect.com/)
  - [机器学习日报](http://ml.memect.com/)
  - [大数据日报](http://bd.memect.com/)
  - [Python日报](http://py.memect.com/)
  - [爱可可老师今日推荐](http://me.memect.com/fly51fly/)
- [Caffe](http://caffe.berkeleyvision.org/)
  - CNN 框架
  - 快速搭建深度学习算法原型并进行训练
  - 提供 Python 与 Matlab 接口
- Scientific Python
  - [Numpy](http://www.numpy.org/) 基础科学计算库
  - [Theano](http://deeplearning.net/software/theano/)
    - ML && DL 基础计算库
    - 快速算法原型搭建
  - [Pandas](http://pandas.pydata.org/)
    - 结构化数据清洗与处理
    - 配合 [matplotlib](http://matplotlib.org/) 做数据可视化
  - [Scrapy](http://scrapy.org/)
    - 网络数据采集与清洗
    - 结构化数据输出供后续应用
  - [Anaconda](https://www.continuum.io/downloads)
    - Python 科学计算集成发行版
    - 包含众多 Python 科学计算相关的库
- awesome [dl][dl] list in github

### Libraries

- [OpenCV][opencv] 计算机视觉基础开发库
  - 基础矩阵运算
  - 图像处理
  - 开发图像与视觉相关的算法或系统
- [OpenMP][openmp] 单机多线程并行计算
  - 单机多核下的并行计算
  - 并行化算法, 提高 CPU 利用率, 减少计算时间
  - 简单的指令便可使串行算法并行化
- [OpenMPI][openmpi] 多机并行计算
  - 多机下的并行计算
  - 可拓展性强, 算法复杂
- [CUDA][cuda] GPU 并行计算
  - GPU 下的并行计算
  - CUDA 是一门编程语言

### Linux

- Linux 操作系统
  - Linux 基本命令集使用
  - 熟悉 Linux 文件系统, 用户权限管理, 网络配置, 路由配置
  - 管理和使用 Linux 服务器
  - 熟悉 Linux 包管理机制及其工具链
  - 熟练运用 gcc 工具链进行源码编译
  - Shell/Python 日常脚本编写
  - C/C++ 跨平台代码编写
  - 大规模数据处理与模型训练的运行环境
  - vim [快捷键工具可参考][vim]
- [Ubuntu][ubuntu]
  - 目前用户量最大的 Linux 发行版, 社区比较大, 资源比较多, 适合 Linux 入门
- [CentOS][centos]
  - 红帽开源代码的再编译
  - 企业服务器用这个系统的比较多, 我们自己的服务器上也装了这个系统
  - 软件源中的软件版本非常低, 大部分库与工具自己用 gcc 编译
- [VirtualBox][vbox]
  - 开源免费的虚拟机运行平台
- [Vagrant][vagrant]
  - 虚拟机管理工具集
  - 方便统一和分发项目的 Linux 开发环境

### Kinect

- Microsoft 开发的3D体感设备，可捕捉彩色图像，深度信息，骨骼动作和面部器官状态
- [官网API介绍][kinect官网API]
- [论坛][Kinect论坛]
- [博客一][kinect博客1]
- [博客二][kinect博客2]


### MFC

- 以C++类的形式封装了Windows API，并且包含一个应用程序框架, 多用于界面
- [windows 消息机制原理][消息机制]
- 《windows 程序设计》
- [MFC编程入门教程][鸡啄米]
- [实时动态曲线描绘控件][动态曲线控件]
- MFC 默认有内存泄露检测的功能, 每个文件可加入下面的代码，这个很赞。
  ```c++

  #ifdef _DEBUG
  #define new DEBUG_NEW
  #endif

  ```

  在含有以上代码的cpp文件中分配内存后假如没有删除，那么停止程序的时候，VisualStudio的Output窗口就会显示如下的信息了：
  ```c++

  Detected memory leaks!
  Dumping objects ->
  d:\code\mfctest\mfctest.cpp(80) : {157} normal block at 0x003AF170, 4 bytes long.
   Data: < > 00 00 00 00
  Object dump complete.

  ```
  在Output窗口双击粗体字那一行，那么IDE就会打开该文件，定位到该行，很容易看出是哪出现了内存泄露。

### To Be Continued……


[coursera]: https://www.coursera.org/
[udacity]: https://www.udacity.com/
[edx]: https://www.edx.org/
[ml-ng]: https://www.coursera.org/learn/machine-learning
[ng]: http://www.andrewng.org/
[uda-git]: https://www.udacity.com/course/how-to-use-git-and-github--ud775
[uda-cv]: https://www.udacity.com/course/introduction-to-computer-vision--ud810
[open-163]: http://open.163.com/
[opencv]: http://opencv.org/
[openmp]: http://openmp.org/wp/
[openmpi]: http://www.open-mpi.org/
[cuda]: https://developer.nvidia.com/cuda-zone
[ubuntu]: http://www.ubuntu.org.cn/
[vbox]: https://www.virtualbox.org/
[vagrant]: https://www.virtualbox.org/
[sf-ab]: http://open.163.com/special/opencourse/abstractions.html
[centos]: https://www.centos.org/
[鸡啄米]:http://www.jizhuomi.com/software/257.html
[vim]:https://github.com/amix/vimrc
[动态曲线控件]:http://blog.csdn.net/nuaazdh/article/details/7857223
[消息机制]:http://winprog.org/tutorial/zh/start_cn.html
[Kinect论坛]:http://guoming.me/kinect2
[kinect官网API]:https://msdn.microsoft.com/en-us/library/dn799271.aspx?tduid=(7b855072b4348da13a3f83e9f9d2f339)(256380)(2459594)(TnL5HPStwNw-8JxCC.2UebmmOxAGOzCD4w)()
[kinect博客1]:http://blog.csdn.net/dustpg/article/category/2408183/2
[kinect博客2]:https://kheresy.wordpress.com/kinect-for-windows-v2-cpp-index/
<<<<<<< HEAD
[dl]:https://github.com/ty4z2008/Qix/blob/master/dl.md
=======
[spyder]: https://github.com/spyder-ide/spyder
[pycharm]: https://www.jetbrains.com/pycharm/
[matlab]: http://cn.mathworks.com/products/matlab/
[vim]: http://www.vim.org/
[emacs]: https://www.gnu.org/software/emacs/
[sublime]: http://www.sublimetext.com/
[notepad++]: https://notepad-plus-plus.org/
[vs]: https://www.visualstudio.com/
[codeblocks]: http://www.codeblocks.org/
[eclipse]: https://eclipse.org/
>>>>>>> 19e47e24b455dc74b94eda3d964303a3adafecac
