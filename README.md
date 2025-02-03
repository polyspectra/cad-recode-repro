An attempt to reproduce "CAD Recode"
https://github.com/filaPro/cad-recode/
https://huggingface.co/datasets/filapro/cad-recode
https://huggingface.co/filapro/cad-recode

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
   pip install datasets ipykernel
   ```

5. Set up Jupyter kernel:
   ```bash
   python -m ipykernel install --user --name=recode --display-name="ReCode"
   ```

6. Open Jupyter notebook and select the "ReCode" kernel

## Development

The project uses:
- Python virtual environment (directory: `venv/`)
- Hugging Face datasets library
- Jupyter notebooks


