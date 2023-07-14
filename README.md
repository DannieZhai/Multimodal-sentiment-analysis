# Multimodal-sentiment-analysis

本次实验为数据学院人工智能课程的最后一次实验：多模态融合情感分析实验。

## setup

以下是我们需要用到的包：

- pytorch==1.11.0
 
- sklearn==1.0.2
 
- transformers==4.30.2
 
- spicy==1.5.4
 
- numpy==1.19.0

我们也可以直接运行：

```python
pip install -r requirements.txt
```
## 仓库结构    

简单描述一下：

```python
|-- data/ # 已知的数据集
|-- main.ipynb# 我的主函数
|-- predict.txt  #预测文件
|-- train.txt # 训练集数据
|-- test_without_label.txt  #测试集数据
|-- requirements.txt 
|-- README.md
|-- 10205501418实验报告.pdf #报告
```

## 运行方法   

直接重启ipynb文件内核，开始训练。   

也可以写作一个python文件，直接：

```python
python main.py 
```
  
## 感谢   
- [LINKX](https://github.com/YeexiaoZheng/Multimodal-Sentiment-Analysis)
- [LINKX](https://github.com/Jankeeeeee/multimodal-sentiment-analysis/blob/main/process_data.ipynb)
