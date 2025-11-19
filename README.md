# Data Analysis Projects

数据分析项目集合，包含探索性数据分析、统计推断和可视化案例。

## 🚀 快速开始

### 环境配置

本项目使用 Nix 进行环境管理，确保依赖一致性。

```bash
# 进入开发环境
nix develop

# 启动 Jupyter Notebook
jupyter notebook
```

## 📊 项目列表

### 1. [纽约市 Airbnb 数据分析](./notebook/airbnb-nyc-analysis)

对 2019 年纽约市 Airbnb 数据进行全面的探索性分析和统计推断。

**关键内容**:
- ✅ 探索性数据分析 (EDA)
- ✅ 描述性统计与可视化
- ✅ 假设检验（t检验、相关性分析）
- ✅ 业务洞察与建议

**技术栈**: Python, Pandas, Matplotlib, Seaborn, SciPy

👉 [查看详细文档](./notebook/airbnb-nyc-analysis/README.md)

## 🛠️ 技术栈

- **语言**: Python 3.11+
- **数据处理**: pandas, numpy
- **可视化**: matplotlib, seaborn
- **统计分析**: scipy
- **环境管理**: Nix Flakes

## 📁 项目结构

```
.
├── flake.nix                    # Nix 配置
├── flake.lock                   # 依赖锁定
├── nix/                         # Nix 配置文件
│   └── dev-shell/
│       └── default.nix          # 开发环境定义
├── airbnb-nyc-analysis/         # NYC Airbnb 分析项目
│   ├── data/                    # 数据文件
│   ├── demo.ipynb              # 分析笔记本
│   └── README.md               # 项目文档
├── setup.py                     # Python 打包配置
└── README.md                    # 项目主文档
```


### 创建新项目

1. 在根目录创建新文件夹
2. 添加 `README.md` 说明文档
3. 创建 Jupyter Notebook 或 Python 脚本
4. 在主 README 中添加项目链接

## 📝 许可

本项目仅供学习和研究使用。

