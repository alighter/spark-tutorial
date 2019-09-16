# Spark Introduction
Content:
- [A. Introduction](#introduction)
- [B. Setup spark standalone](#standalone)
- [C. Setup environment for practicing spark locally](#practice)

### A. Introduction <a name="introduction"></a>

### B. Setup spark standalone <a name="standalone"></a>
This guideline is a basic setup for standalone. It will help you how to setup and start master and worker on your computer.

1. 


### C. Setup environment for practicing spark locally <a name="practice"></a>
This guideline will help you setup virtual environment, install pyspark and jupyterlab for practice

1. Setup virtual environment
- Install virtualenv by pip in ubuntu, open terminal and type:
    ```
    pip install virtualenv
    ```
- Create virtual environment for project:
    ```
    # go to your project
    cd your_project
    # create virtualenv with python 3.6
    virtualenv -p /usr/bin/python3.6 venv
    ```
- Active your venv
    ```
    source venv/bin/activate
    ```
- Now, you had an activate environment for development, you can install libraries into `venv`. To deactivate:
    ```
    deactivate
    ``` 
2. Install pyspark into `venv`
    ```
    pip install pyspark
    ```

3. Install jupyterlab into `venv` and practice
- Install jupyterlab
    ```
    pip install jupyterlab
    ```
- Start jupyterlab
    ```
    jupyter lab
    ```
    