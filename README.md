An attempt to reproduce "CAD Recode"
- [GitHub Repository](https://github.com/filaPro/cad-recode/)
- [Dataset on Hugging Face](https://huggingface.co/datasets/filapro/cad-recode)
- [Model on Hugging Face](https://huggingface.co/filapro/cad-recode)

## Requirements
- Python 3.9 or higher (tested with Python 3.11)

## Setup Instructions

1. Ensure you have Python installed. You can check with:
   ```bash
   python --version  # Should be 3.9 or higher
   ```

2. Create a virtual environment:
   ```bash
   python -m venv venv
   ```

3. Activate the virtual environment:
   ```bash
   # On Mac/Linux
   source venv/bin/activate

   # On Windows
   # venv\Scripts\activate
   ```

4. Install required packages:
   ```bash
   pip install datasets ipykernel huggingface-cli
   ```

5. Set up Jupyter kernel:
   ```bash
   python -m ipykernel install --user --name=recode --display-name="ReCode"
   ```

6. Login to Hugging Face (recommended for better download rates):
   ```bash
   huggingface-cli login
   # You'll need a token from: https://huggingface.co/settings/tokens
   ```

7. Download the dataset:
   ```bash
   # Create datasets directory (it's gitignored)
   mkdir datasets

   # Download the dataset
   huggingface-cli download --repo-type dataset filapro/cad-recode --local-dir datasets/cad-recode
   ```

8. Open Jupyter notebook and select the "ReCode" kernel

## Development

The project uses:
- Python virtual environment (directory: `venv/`)
- Hugging Face datasets library
- Jupyter notebooks


