# Visual system
基于YOLO11的八段锦课堂学生行为识别可视化系统

功能说明
  ![bbccf7b423f2aebd493c1d11fb799a7](https://github.com/user-attachments/assets/4c973a6b-f17b-4f9d-9532-3edcf3292985)
  本研究基于Windows 11系统选用了PyQt5工具设计了图形用户界面（Graphical User Interface，GUI），与学生课堂行为识别模型相结合，对识别结果进行分析并展示。
  系统的功能架构设计旨在实现简洁、高效、准确的课堂行为分析，主要包含以下两个核心功能：
  行为识别 学生课堂行为识别功能作为系统核心，将本研究提出的识别模型与系统深度结合，具备延时与实时监测学生课堂行为的能力。用户可通过检测图片、视频或摄像头上传图像信息，选择识别模型并启动检测。系统以每秒一次的频率处理输入，快速且精准地完成识别，为用户提供即时反馈。
  结果统计 系统能够高效整理与分析识别结果，并以直观图表呈现数据。此外，系统提供数据保存功能，便于用户导出结果后进行分析或存档，导出结果如上图所示。

安装教程
  安装 PyQt5： 本研究通过 PyCharm 的设置安装
  点击 File -> Settings。
  在设置界面中，选择 Project -> Python Interpreter。
  点击右侧的 + 按钮，搜索 PyQt5。
  选择 PyQt5 并点击 Install Package 安装。
  安装完成后，PyCharm 会自动识别并添加 PyQt5 到项目中。
  检查安装是否成功： 通过在终端中运行 pip list 查看是否安装了 PyQt5。

  在 PyCharm 中编写PyQt5 应用程序
  创建 Python 文件：    
  在 PyCharm 项目中，右键点击项目文件夹，选择 New -> Python File，将文件命名为 main.py。
  编写代码： 在新建的 main.py 文件中，输入本系统以下代码：具体代码在论文录用后上传
