# Takeout Order Forecast

## 项目简介

基于机器学习的外卖订单量预测系统，旨在通过历史订单数据构建预测模型，为商家运营和平台调度提供数据支撑。

## 技术栈

- Python 3.11
- pandas / numpy — 数据处理与数值计算
- matplotlib / seaborn — 数据可视化
- scikit-learn — 机器学习基础算法与评估
- xgboost — 梯度提升模型
- joblib — 模型序列化

## 运行方法

1. 创建并激活 Conda 虚拟环境：

```bash
conda create -n takeaway python=3.11
conda activate takeaway
```

2. 安装依赖：

```bash
pip install -r requirements.txt
```

3. 运行主程序：

```bash
python main.py
```

## 项目目录说明

```
takeout-order-forecast/
│
├── data/                   # 数据目录
│   ├── raw/                # 原始数据
│   └── processed/          # 清洗后的数据
│
├── notebooks/              # Jupyter 笔记本（探索性分析）
│
├── src/                    # 源代码
│   ├── data_preprocessing.py   # 数据预处理
│   ├── eda.py                  # 探索性数据分析
│   ├── feature_engineering.py  # 特征工程
│   ├── train.py                # 模型训练
│   ├── evaluate.py             # 模型评估
│   └── predict.py              # 预测推理
│
├── models/                 # 训练好的模型文件
│
├── outputs/                # 输出结果
│   ├── figures/            # 图表
│   └── reports/            # 报告
│
├── requirements.txt        # Python 依赖
├── README.md               # 项目说明
└── main.py                 # 项目入口
```
