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

Buat **simulasi** *state-space* atau *transfer-function* dengan menggunakan, Python, dan numpy, lalu plot hasilnya menggunakan library matplotlib. Soalnya adalah sebagai berikut ([reference](https://www.javatpoint.com/control-system-state-space-model)):

<img src="https://render.githubusercontent.com/render/math?math=%5Cmathbf%7Bx%7D(t)%3D%5Cbegin%7Bbmatrix%7Dx_1(t)%20%26%20x_2(t)%20%26%20x_3(t)%5Cend%7Bbmatrix%7D%5E%5Cmathrm%7BT%7D">

$\dot{\mathbf{x}}(t) = \begin{bmatrix}0 & 1 & 0 \\ 0 & 0 & 1 \\ -10 & -11 & -6 \end{bmatrix}\mathbf{x}(t)+\begin{bmatrix}0\\0\\8\end{bmatrix}u(t)$

$y(t)=\begin{bmatrix}1 & 0 & 0\end{bmatrix}\mathbf{x}(t)$

**Notes**:
1. Pake metode **Euler**
2. *Initial condition* bebas (jangan *zero-initial-condition*)
3. *Input*-nya adalah fungsi step, *gain*-nya bebas
4. *Sampling rate*, $\Delta t=0.01 \, s$
5. $t_{initial}$ dan $t_{final}$ bebas
6. Format *plot* bebas

Yang bebas tolong diseragamin ya. Kode perlu disesuaikan dengan format:

```python
def dynamics(t, x, u):
   '''
   DESC:
      Function untuk ngituing dynamics (x_dot)
   INPUT:
      t : numpy array (1,) atau float, waktu
      x : numpy array (3,), state
      u : numpy array (1,) atau float, input
   OUTPUT:
      x_dot : numpy array (3,), x_dot pada waktu t
   '''

   x_dot = ...

   return x_dot

class Euler():
   def __init__(self, dynamics):
      '''
      DESC:
         Class untuk simulasi dengan metode Euler
      INPUT:
         dynamics : Python function untuk ngitung x_dot
      '''
      
      self.dynamics = dynamics

   def simulate(self, t, x0, u):
      '''
      DESC:
         Method untuk simulasi
      INPUT:
         t : numpy array (N,), waktu simulasi
         x0 : numpy array (3,), initial state
         u: numpy array (N,), input
      OUTPUT:
         t : numpy array (N,), waktu simulasi
         x : numpy array (N, 3), state
         y : numpy array (N,), output
      '''
      

      return t, x, y

# Cara pakenya
sim = Euler(dynamics)
t, x, y = sim.simulate(t, x0, u)
```