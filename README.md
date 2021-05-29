# 1. General Description
Repositori internship Mesin 19 di [ICoDes](https://ik.fti.itb.ac.id/lab-icodes/) (Remote).

**Advisor**: Prof. Yul Yunazwin Nazaruddin

**Mentor**: Fadillah Adamsyah Ma'ani

**Member**:
| No.  |   NIM    |                              Nama |
| :--- | :------: | --------------------------------: |
| 1.   | 13119001 |                    Muhammad Harza |
| 2.   | 13119005 |              Fachriza Afif Ma'ani |
| 3.   | 13119032 |               Muhammad Axel Dhiya |
| 4.   | 13119043 |    Muhammad Akif Miftahun Najakhi |
| 5.   | 13119049 | Georgius Harry Setiawan Soetandyo |

# 2. Table of Contents
- [1. General Description](#1-general-description)
- [2. Table of Contents](#2-table-of-contents)
- [3. Tutorial](#3-tutorial)
  - [3.1. Python](#31-python)
  - [3.2. Installation](#32-installation)
    - [3.2.1. Miniconda](#321-miniconda)
    - [3.2.2. Visual Studio Code](#322-visual-studio-code)
  - [3.3. Machine Learning](#33-machine-learning)
    - [3.3.1. Basic Theory & Practice](#331-basic-theory--practice)
  - [3.4. Git](#34-git)
- [4. Task](#4-task)
  - [4.1. Homework #1](#41-homework-1)

# 3. Tutorial

## 3.1. Python

**Sources**:

1. [learnpython.org](https://www.learnpython.org/):
   - [Hello, World!](https://www.learnpython.org/en/Hello%2C_World%21)
   - [Variables and Types](https://www.learnpython.org/en/Variables_and_Types)
   - [Lists](https://www.learnpython.org/en/Lists)
   - [Basic Operators](https://www.learnpython.org/en/Basic_Operators)
   - [String Formatting](https://www.learnpython.org/en/String_Formatting)
   - [Conditions](https://www.learnpython.org/en/Conditions)
   - [Loops](https://www.learnpython.org/en/Loops)
   - [Functions](https://www.learnpython.org/en/Functions)
   - [Classes and Objects](https://www.learnpython.org/en/Classes_and_Objects)
   - [Dictionaries](https://www.learnpython.org/en/Dictionaries)
   - [Modules and Packages](https://www.learnpython.org/en/Modules_and_Packages)
   - [Numpy Arrays](https://www.learnpython.org/en/Numpy_Arrays)
   - [List Comprehensions](https://www.learnpython.org/en/List_Comprehensions)
   - [Multiple Function Arguments](https://www.learnpython.org/en/Multiple_Function_Arguments)

2. [DataCamp - Python Fundamentals](https://www.datacamp.com/tracks/python-fundamentals)

3. [Jupyter Notebook](https://towardsdatascience.com/a-beginners-tutorial-to-jupyter-notebooks-1b2f8705888a)
   - The Basics of Jupyter Notebooks
   - Adding Descriptive Text to Your Notebook

4. [cs231 - python-numpy-tutorial](https://cs231n.github.io/python-numpy-tutorial/#containers)
   - Numpy
   - Matplotlib

## 3.2. Installation

### 3.2.1. Miniconda

**Why**: Instalasi package Python pada conda relatif lebih mudah dibandingkan dengan pip.

[Download](https://docs.conda.io/en/latest/miniconda.html)

```bash
# Membuat environment pada conda. Disarankan menggunakan environment.
# Apabila ada error, tinggal delete environment nya, ga perlu reinstall conda.
# (-n myenv) --> Nama environment
# (python=3.9) --> Versi Python (3.9.x)
conda create -n myenv python=3.9

# Activate an environment
# (myenv) --> Nama environment
conda activate myenv

# Install package
conda install numpy # Install package numpy
conda install -c intel numpy # Install package numpy pada channel intel
                             # Pakai yang ini kalau CPU kalian Intel.
conda install jupyter # Untuk keperluan jupyter notebook & jupyter lab
conda install -c conda-forge pandas matplotlib # Bisa juga tanpa -c conda-forge

# Btw, di conda juga ada pip, jadi kalian juga bisa pakai
# pip install <package>
# Diutamakan pakai [conda install]. Conda otomatis install dependencies dari suatu package.

# Untuk belajar dan riset, kita bakal sering pakai jupyter notebook atau jupyter lab
jupyter notebook # Buka jupyter notebook
```

### 3.2.2. Visual Studio Code

*Visual Studio Code* adalah suatu *code edittor* yang di dalamnya terdapat *tools* yang mempermudah pengguna saat menulis kode, seperti *autocompletion*, *auto indentation*, *code formatting*, dan *terminal*. Visual studio code ini enak banget buat ngetik dan ngedit kode. Setelah selesai uji coba di Jupyter Notebook, biasanya kode akan dibuat kaya semacam *library* supaya bisa digunakan di pekerjaan selanjutnya. Oleh karena itu, kita bakal bikin kode tersebut di script (.py). 

[Download](https://code.visualstudio.com/Download)

## 3.3. Machine Learning

### 3.3.1. Basic Theory & Practice

**Sources**:

1. [DataCamp - Machine Learning Fundamentals with Python](https://www.datacamp.com/tracks/machine-learning-fundamentals-with-python):
   - [Supervised Learning with scikit-learn](https://www.datacamp.com/courses/supervised-learning-with-scikit-learn)
   - [Unsupervised Learning in Python](https://www.datacamp.com/courses/unsupervised-learning-in-python)
2. [Coursera - Deep Learning Specialization](https://www.coursera.org/specializations/deep-learning#courses):
   - [Neural Networks and Deep Learning](https://www.coursera.org/learn/neural-networks-deep-learning?specialization=deep-learning)
   - [Improving Deep Neural Networks: Hyperparameter Tuning, Regularization and Optimization](https://www.coursera.org/learn/deep-neural-network?specialization=deep-learning)

## 3.4. Git

# 4. Task

## 4.1. Homework #1

