# Machine-Generated-Text-Detection
Building and evaluating machine learning models to classify whether a given text is human-written or machine-generated, using data from the SemEval 2024 Task 8 (Subtask A), with a focus on binary classification of English texts.

## Setting up a Virtual Environment
To keep your dependencies organized and avoid conflicts, it's recommended to use a virtual environment.

1. **Create a virtual environment:**

```bash
python3 -m venv env
```

2. **Activate the virtual environment:**

- On Linux/Mac:

```bash
source env/bin/activate
```

- On Windows:

```bash
env\Scripts\activate
```

3. **Install the required packages:**

Make sure you have a `requirements.txt` file listing all dependencies. Then run:

```bash
pip install -r requirements.txt
```

4. **Deactivate the virtual environment when done:**

```bash
deactivate
```

This ensures your work environment stays clean and reproducible.

## Setting up the Dataset Folder
To organize your data, create a `dataset` folder and include the necessary files for Subtask A.

1. **Create the folder:**

```bash
mkdir dataset
```

2. **Add the following files to the folder:**

- `subtaskA_train_monolingual.jsonl` — Training data for Subtask A
- `subtaskA_monolingual.jsonl` — Gold standard (test) data for Subtask A

Ensure these files are properly formatted and placed in the `dataset` folder before running any training or evaluation scripts.

