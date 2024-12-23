# Load and inspect the contents of the uploaded files to understand their structure and purpose

file_paths = {
    "NER SVM": "/mnt/data/NER SVM.ipynb",
    "POS Tagging (CRF Based)": "/mnt/data/POS Tagging (CRF Based).ipynb",
    "POS Tagging (HMM Based)": "/mnt/data/POS Tagging (HMM Based).ipynb"
}

# Read the contents of the uploaded files
import nbformat

notebooks = {}
for name, path in file_paths.items():
    with open(path, 'r') as f:
        notebooks[name] = nbformat.read(f, as_version=4)

# Analyze the notebook contents to summarize them
notebook_summaries = {name: [cell['source'] for cell in nb['cells'] if cell['cell_type'] == 'markdown'] for name, nb in notebooks.items()}
notebook_summaries
