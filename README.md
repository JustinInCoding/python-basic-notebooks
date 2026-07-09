# python-basic-notebooks

《Python编程：从入门到实践（第3版）》学习代码操练

## 环境配置

本项目使用 Conda 进行环境管理。推荐使用 Miniconda 或 Anaconda 来创建独立的学习环境。

### 1. 创建 Conda 环境

```bash
# 创建名为 python-learning 的环境，Python 版本为 3.11
conda create -n python-learning python=3.11 -y
```

### 2. 激活环境

```bash
# 激活环境
conda activate python-learning

# 验证 Python 版本
python --version
```

### 3. 安装常用库（可选）

根据学习进度安装常用的 Python 库：

```bash
# 数据科学相关库
conda install numpy pandas matplotlib jupyter -y

# Web 开发相关库（如学习 Django 项目时）
conda install django -y

# 游戏开发相关库（如学习外星人入侵游戏时）
conda install pygame -y
```

### 4. 环境管理常用命令

```bash
# 查看所有环境
conda env list

# 停用环境
conda deactivate

# 导出环境配置
conda env export > environment.yml

# 从配置文件创建环境
conda env create -f environment.yml

# 删除环境
conda env remove -n python-learning
```

## 项目结构

随着学习进度，项目将包含以下内容：

- 基础语法练习
- 数据结构练习  
- 面向对象编程练习
- 项目实战代码

## 学习资源

- 教材：《Python编程：从入门到实践（第3版）》
- Python 官方文档：https://docs.python.org/zh-cn/3/
