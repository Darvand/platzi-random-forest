# Platzi Random Forest

Predict whether income exceeds $50K/yr based on census data using a random forest model

## Create environment

```bash
conda env create -f environment.yml
activate platzi_random_forest
```

To move beyond notebook prototyping, all reusable code should go into the `modules/` folder package. To use that package inside your project, install the project's module in editable mode, so you can edit files in the `modules` folder and use the modules inside your notebooks :

```bash
pip install --editable .
```

To use the module inside your notebooks, add %autoreload at the top of your notebook :

```python
%load_ext autoreload
%autoreload 2
```

Example of module usage:

```python
from modules.utils.paths import data_dir
data_dir()
```

## License
