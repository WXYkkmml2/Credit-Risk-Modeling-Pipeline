# Credit-Risk-Modeling-Pipeline
项目目标: 在一个真实的信贷数据集上，搭建一个从数据预处理、特征工程、模型训练到验证与解释的完整风控建模流水线。最终产出一个逻辑回归评分卡和一个更高性能的机器学习模型（如XGBoost）。
The goal of this project: To build a pineline of data preprocessing , feature engineering, model training to validation and interpretation by the real world credit dataset.The output is a Logistic Regression Score Card Logistic Regression Score Card and a machine learning model (XGBoot) with higher performence.

The design step:
1.get data and EDA（探索式数据分析，用于查看数据在形式建模或假设任务之外能够提示的内容，并提供对数据集变量及其之间关系的更好理解）:
# 信贷风险建模项目 (Credit Risk Modeling Pipeline)

这是一个用于学习和实践信贷风控建模全流程的项目。

## 🚀 开发环境快速设置 (Quickstart)

请按照以下步骤来设置和启动项目环境。

1.  **创建并激活虚拟环境:**
    ```bash
    # 创建 (仅需在项目初始化时运行一次)
    python3 -m venv .venv

    # 激活 (每次开始工作时都需要运行)
    source .venv/bin/activate
    ```

2.  **安装项目依赖库:**
    (确保虚拟环境已激活)
    ```bash
    pip install -r requirements.txt
    ```
    *注意: `requirements.txt` 需要通过 `pip freeze > requirements.txt` 命令生成。*

3.  **启动Jupyter Notebook:**
    (确保虚拟环境已激活)
    ```bash
    jupyter notebook notebooks/
    ```

4.  **退出虚拟环境:**
    (当你完成工作后)
    ```bash
    deactivate
    ```