<div align="center">
<a name="readme-top"></a>

# Exercism 编程练习

**[English](./README.md)** · 简体中文

<!-- Badges -->
<p>
  <img src="https://img.shields.io/badge/platform-exercism-blue.svg" alt="platform">
  <img src="https://img.shields.io/badge/language-python-yellow.svg" alt="language">
  <img src="https://img.shields.io/badge/tests-pytest-green.svg" alt="tests">
  <img src="https://img.shields.io/badge/license-MIT-brightgreen.svg" alt="license">
</p>

</div>

本仓库包含我在 [Exercism](https://exercism.org/) 平台上完成的编程练习和解决方案。

## 📋 目录

- [Exercism 编程练习](#exercism-编程练习)
  - [📋 目录](#-目录)
  - [🌟 简介](#-简介)
  - [ℹ️ 什么是 Exercism？](#ℹ️-什么是-exercism)
  - [📁 仓库结构](#-仓库结构)
  - [🔧 如何运行测试](#-如何运行测试)
    - [Python 练习](#python-练习)
  - [✅ 目前完成的练习](#-目前完成的练习)
  - [📝 学习笔记](#-学习笔记)
  - [📄 许可证](#-许可证)

## 🌟 简介

本仓库包含我在 [Exercism](https://exercism.org/) 平台上完成的编程练习和解决方案。

## ℹ️ 什么是 Exercism？

Exercism 是一个免费的编程学习平台，提供了多种编程语言的练习题和指导。通过完成这些练习，可以提高编程技能并接收社区的反馈。

## 📁 仓库结构

每种编程语言都有自己的目录，每个练习都是该语言目录下的一个子目录：

```
language/
  exercise-name/
    README.md - 练习的说明
    HELP.md - 帮助文档
    exercise_test.py - 测试文件
    exercise.py - 解决方案
```

## 🔧 如何运行测试

### Python 练习

对于 Python 练习，我们使用 pytest 进行测试：

1. 确保已安装必要的依赖：

```bash
pip install -r requirements.txt
```

2. 进入练习目录：

```bash
cd python/exercise-name
```

3. 运行测试：

```bash
python -m pytest -o markers=task exercise_test.py
```

或使用unittest方式：

```bash
python -m unittest exercise_test.py
```

## ✅ 目前完成的练习


## 📝 学习笔记

- 测试文件通常命名为 `exercise_test.py` 格式
- Exercism Python练习支持Python 3.7-3.11.5版本

## 📄 许可证

本项目是开源的，采用MIT许可证。

<div align="center">
  <p>
    <a href="#exercism-编程练习">返回顶部</a>
  </p>
</div>