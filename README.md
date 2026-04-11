## Requirements

We recommend using the following environment:

- Python: 3.7
- PyTorch 1.11.0+cu113
- Transformers 4.12.0
- NumPy 1.21.6
- tqdm 4.67.1
- sentencepiece 0.2.0
- PyTorch Lightning: 1.3.5
- spacy==3.4.4
- en-core-web-sm==3.4.0

## Installation

We recommend creating a new conda environment first:

```bash
conda create -n msws python=3.7 -y
conda activate msws

pip install torch==1.11.0+cu113 torchvision==0.12.0+cu113 torchaudio==0.11.0+cu113 --extra-index-url https://download.pytorch.org/whl/cu113
pip install -r requirements.txt

MSWS/
├── README.md
├── requirements.txt
├── main.py
├── data_utils.py
├── eval_utils.py
├── data/
│   ├── restaurant-acos/
│   ├── laptop-acos/
│   └── shoes-acos/


