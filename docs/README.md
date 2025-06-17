FinTech-Risk-Models/

├── data/                   # 存放数据（勿传原始数据！）

│   ├── processed/          # 清洗后数据

│   └── raw/                # 仅放数据获取脚本（如API调用代码）

├── docs/                   # 项目文档

│   ├── 业务价值报告.pdf      # 关键！说明解决什么金融问题

│   └── 合规声明.md          # 标注符合的监管条款

├── models/                 # 训练好的模型

│   ├── scoring_card.pkl    # 评分卡模型

│   └── var_calculator.py   # VaR计算工具

├── notebooks/              # 分析过程

│   └── EDA.ipynb           # 探索性数据分析

├── src/                    # 源代码

│   ├── data_processing.py

│   ├── model_training.py

│   └── deployment.py

├── .gitignore              # 忽略敏感文件

├── LICENSE

└── README.md               
