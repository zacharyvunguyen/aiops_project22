## Configuration:

### Clone source code from repo:

```python
https://github.com/zacharyvunguyen/mlops_project.git
```
### Create run time environment for project
```python
 conda create -p venv python==3.7 -y
```

### Activate the new created environment
```python
conda activate venv/
```
### Create .gitignore
```python
 touch .gitignore
```
### Install libraries
```python
pip install jupyter lab
```

### Create requirement.txt file
```python
pip freeze>requirement.txt
```
### Install libraries from requirement.txt file
```python
pip install -r requirement.txt
```
## How to run pipeline build using TFX

1. Interactive Context
2. LocalDagRunner
3. BeamDagRunner
4. Airflow
5. Kubeflow