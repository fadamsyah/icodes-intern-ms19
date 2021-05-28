# Description
Repositori internship Mesin 19 di [ICoDes](https://ik.fti.itb.ac.id/lab-icodes/) (Remote).

**Member**:
| No.  |   NIM    |                              Nama |
| :--- | :------: | --------------------------------: |
| 1.   | 13119001 |                    Muhammad Harza |
| 2.   | 13119005 |              Fachriza Afif Ma'ani |
| 3.   | 13119032 |               Muhammad Axel Dhiya |
| 4.   | 13119043 |    Muhammad Akif Miftahun Najakhi |
| 5.   | 13119049 | Georgius Harry Setiawan Soetandyo |

**Advisor**: Prof. Yul Yunazwin Nazaruddin

**Mentor**: Fadillah Adamsyah Ma'ani

# Tutorial

## Python

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

## Installation

### Miniconda

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

### Visual Studio Code

**Why**: Setelah selesai uji coba, biasanya kode akan dibuat kaya semacam *library* supaya bisa digunakan di pekerjaan selanjutnya. Oleh karena itu, kita bakal bikin kode tersebut di script (.py). Visual studio code ini enak banget buat ngetik dan ngedit.

[Download](https://code.visualstudio.com/Download)

## Machine Learning