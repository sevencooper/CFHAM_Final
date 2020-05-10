# Computing for Health and Medicine Final

This notebook is based off of Sebastian Pölsterl's Survival Analysis for Deep Learning blog post which can be found [here](https://k-d-w.org/blog/2019/07/survival-analysis-for-deep-learning/#cox-s-proportional-hazards-model).\

**I've left all of the original comments from Sebastian's Notebook but I've added several comments to more explicitly explain the code.**

## Dependency Installation

Prior to executing this notebook, the neccessary dependencies must be installed.
Run the below command to install all dependencies in one line:
```python
pip install -r requirements.txt
```
This may take ~5-15 minutes to run.\
Make sure to inspect the output of the run to see if all dependencies were successfully installed.\
In my case, I had to update scipy before installing tensor flow
```python
pip install --upgrade scipy
```
Install Anaconda and launch Anaconda prompt as Administrator.\
run the following:
```python
pip install tensorflow==1.15.2 # This will downgrade your TensorFlow to 1.15.2!!
cd ./path/to/notebook
jupyter notebook
```
This should open a Jupyter Notebook instance in your browser.\
The notebook can then be executed (expect this to take around 30 minutes).