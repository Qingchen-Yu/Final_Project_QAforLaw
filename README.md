## 模型部分
微调方式：
lora：运行文件 train.sh
pt：运行文件 train_pt.sh
运行的结果/权重会保存在对应的目录

测试方式：
在测试集上测试：运行 test.sh
单条数据测试：python test_infer.py
api测试：首先 python run_api.py 然后 python test_post.py


## rag部分


## 数据部分
自行设置数据集路径 并在运行的文件对应位置调整参数
格式是：{context:prompt+问题,lable:问题答案}


## 网页部署