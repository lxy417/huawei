# 系统实现
首先安装bert as service

pip install  bert-serving-server

pip install bert-serving-client

下载模型链接：https://pan.baidu.com/s/1PZsZ8pUlYRRTQ4NoD42a9A 

提取码：diC7  

把下载好的这个文件放到model目录下

打开终端输入  bert-serving-start  -model_dir path -num_worker=2

path是bert模型路径，例如E:/model

然后进入all.py文件更改相应的model路径

运行就好了
