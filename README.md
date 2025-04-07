# Exercism 编程练习 | Exercism Programming Exercises

## 简介 | Introduction

这个仓库包含我在 [Exercism](https://exercism.org/) 平台上完成的编程练习和解决方案。
This repository contains my programming exercises and solutions completed on the [Exercism](https://exercism.org/) platform.

## 什么是 Exercism？ | What is Exercism?

Exercism 是一个免费的编程学习平台，提供了多种编程语言的练习题和指导。通过完成这些练习，可以提高编程技能并接收社区的反馈。
Exercism is a free programming learning platform offering exercises and guidance in multiple programming languages. By completing these exercises, you can improve your programming skills and receive feedback from the community.

## 仓库结构 | Repository Structure

每种编程语言都有自己的目录，每个练习都是该语言目录下的一个子目录：
Each programming language has its own directory, and each exercise is a subdirectory under that language:

```
language/
  exercise-name/
    README.md - 练习的说明 | Exercise description
    HELP.md - 帮助文档 | Help documentation
    exercise_test.py - 测试文件 | Test file
    exercise.py - 解决方案 | Solution
```

## 如何运行测试 | How to Run Tests

### Python 练习 | Python Exercises

对于 Python 练习，我们使用 pytest 进行测试：
For Python exercises, we use pytest for testing:

1. 确保已安装必要的依赖：
   Ensure necessary dependencies are installed:

```bash
pip install -r requirements.txt
```

2. 进入练习目录：
   Navigate to the exercise directory:

```bash
cd python/exercise-name
```

3. 运行测试：
   Run the tests:

```bash
python -m pytest -o markers=task exercise_test.py
```

或使用unittest方式：
Or using unittest:

```bash
python -m unittest exercise_test.py
```

## 目前完成的练习 | Completed Exercises

### Python
- hello-world - 基础入门练习 | Basic introductory exercise

## 学习笔记 | Learning Notes

- Python 练习需要返回结果而不是打印结果
  Python exercises require returning results instead of printing them

- 测试文件通常命名为 `exercise_test.py` 格式
  Test files are usually named in the `exercise_test.py` format

- Exercism Python练习支持Python 3.7-3.11.5版本
  Exercism Python exercises support Python versions 3.7-3.11.5