# Getting started with jupyter notebook using poetry kernel
---
## [Link for this documentation](https://www.youtube.com/watch?v=Nj87GEXxhjc)

<https://www.youtube.com/watch?v=jeOfS90Flf8&t=582s>

### _Steps to get started with jupyter notebook using `poetry` as virtual environment and package management tool_

* Create a new `poetry project`

```python
poetry new my_project
```
* Change directory to newly created project

```python
cd my_project
```
* Create a new `poetry virtual environment`

```python
poetry shell
```
* Install `Jupyter Notebook`

```python
poetry add jupyter
```
* Install `ipykernel` to make the virtual environment availabe as a kernel in Jupyter

```python
poetry add ipykernel
```
* Add the virtual environment as a `Jupyter Kernel`

```python
python -m ipykernel install --user --name=my_project
```
* Open project in `VS Code`

```python
code .
```
* Select the kernel in VS Code
    * Create a Jupyter Notebook file with .ipynb extension
    * Go to kernel options in the top right corner of the notebook
    * Choose the kernel you created earlier (e.g. my_project)

* Start using Jupyter Notebook
    * Start using Jupyter Notebook within `VS Code` with your `Poetry Virtual Environment`
