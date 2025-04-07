<div align="center">
<a name="readme-top"></a>

# Exercism Programming Exercises

**English** · [简体中文](./README.zh-CN.md)

<!-- Badges -->
<p>
  <img src="https://img.shields.io/badge/platform-exercism-blue.svg" alt="platform">
  <img src="https://img.shields.io/badge/language-python-yellow.svg" alt="language">
  <img src="https://img.shields.io/badge/tests-pytest-green.svg" alt="tests">
  <img src="https://img.shields.io/badge/license-MIT-brightgreen.svg" alt="license">
</p>

</div>

This repository contains my programming exercises and solutions completed on the [Exercism](https://exercism.org/) platform.

## 📋 Table of Contents

- [Exercism Programming Exercises](#exercism-programming-exercises)
  - [📋 Table of Contents](#-table-of-contents)
  - [🌟 Introduction](#-introduction)
  - [ℹ️ What is Exercism?](#ℹ️-what-is-exercism)
  - [📁 Repository Structure](#-repository-structure)
  - [🔧 How to Run Tests](#-how-to-run-tests)
    - [Python Exercises](#python-exercises)
  - [📝 Learning Notes](#-learning-notes)
  - [📄 License](#-license)

## 🌟 Introduction

This repository contains my programming exercises and solutions completed on the [Exercism](https://exercism.org/) platform.

## ℹ️ What is Exercism?

Exercism is a free programming learning platform offering exercises and guidance in multiple programming languages. By completing these exercises, you can improve your programming skills and receive feedback from the community.

## 📁 Repository Structure

Each programming language has its own directory, and each exercise is a subdirectory under that language:

```
language/
  exercise-name/
    README.md - Exercise description
    HELP.md - Help documentation
    exercise_test.py - Test file
    exercise.py - Solution
```

## 🔧 How to Run Tests

### Python Exercises

For Python exercises, we use pytest for testing:

1. Ensure necessary dependencies are installed:

```bash
pip install -r requirements.txt
```

2. Navigate to the exercise directory:

```bash
cd python/exercise-name
```

3. Run the tests:

```bash
python -m pytest -o markers=task exercise_test.py
```

Or using unittest:

```bash
python -m unittest exercise_test.py
```


## 📝 Learning Notes

- Test files are usually named in the `exercise_test.py` format
- Exercism Python exercises support Python versions 3.7-3.11.5

## 📄 License

This project is open source and available under the MIT License.

<div align="center">
  <p>
    <a href="#exercism-programming-exercises">Back to Top</a>
  </p>
</div>