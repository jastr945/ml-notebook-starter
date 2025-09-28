# ml-notebook-starter
Minimal code to start an ML project

## Repo structure

| Section      | Purpose                                                                  |
| ------------ | ------------------------------------------------------------------------ |
| `notebooks/` | Use for step-by-step development, exploration, and documentation         |
| `src/`       | Modular, reusable code (e.g., feature extraction, training logic)        |
| `data/`      | Organized into raw → processed → modeling-ready                          |
| `models/`    | Store trained model checkpoints                                          |
| `results/`   | Store metrics, visualizations, and attribution outputs                   |
| `configs/`   | YAML or JSON configs for reproducibility                                 |
| `README.md`  | Explain how to run notebooks, install dependencies, and expected outputs |


## Local setup

To get started, clone the repository and navigate into the project directory:
```sh
git clone git@github.com:jastr945/ml-notebook-starter.git
cd ml-notebook-starter
```
Optionally, you can rename the folder as you clone it.

Create a virtual environment:
```sh
python3 -m venv venv
source venv/bin/activate
```
Install the required packages using pip:
```sh
pip install -r requirements.txt
```
Since we are using Jupyter, also register your environment as a kernel:
```sh
python -m ipykernel install --user --name=test --display-name "Python test"
```
Launch JupyterLab:
```sh
jupyter lab
```