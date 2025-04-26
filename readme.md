## Use Python 3.11.9

### Open the project in Visual Studio Code
```bash
code .
```


### # Create a virtual environment named 'venv'
```bash
python -m venv venv

# Activate the virtual environment (Windows)
./venv/Scripts/activate
```


### Install the required dependencies
```bash
pip install -r requirements.txt
```

### Run the project
1. Open the main.ipynb file
2. Select kernel >> python environment >> with the venv option
3. Change it if you want to run sample data
```py
# Let's look at the training data
# train_df = pd.DataFrame(dataset['train'])

# Take only the first 100 rows of the training data
train_df = pd.DataFrame(dataset['train'][:100])
```

4. Run All