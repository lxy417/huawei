# 系统实现
首先安装bert as service

pip install  bert-serving-server

pip install bert-serving-client

打开终端输入  bert-serving-start  -model_dir path -num_worker=2

path是bert模型路径，例如E:/model

然后进入all.py文件更改相应的model路径

运行就好了
