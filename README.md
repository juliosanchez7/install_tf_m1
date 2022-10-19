# Tensorflow Installation (Mac on Apple Metal M1)
# Install Jupyter and Create Environment

Desativate base enviroment

```
conda deactivate
```
Create enviroment with the yml file with all the set up for mac with M1 

```
conda env create -f tensorflow-apple-metal-conda.yml -n tensorflow
```
Activate the enviroment

```
conda activate tensorflow
```
Install jupyter lab

```
pip install jupyterlab
```
Create an specific kernel to the enviroment

```
pip install ipykernel
python -m ipykernel install --user --name=tensorflow
```
Open jupyter lab
```
jupyter lab
```
