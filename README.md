# Football-Prediction
### Project Structure

```
.
├── README.md
├── requirements.txt
├── models/                    # Directory storing all notebooks, notebooks containing more important code will be outside sub directories
├── scratch work/              # Directory storing notebooks which Contained work, but not the finalized models
│   ├── dataset-tesing.ipynb    # notebook containing graphics for project proposal
│   ├── looking_at_something.ipynb # notebook containing stats regarding outcomes conditional on half time results
│   ├── main-work.ipynb        # notebook that was worked on before we realized we were answering the wrong question in it
│   └── try-again.ipynb        # notebook that was later revised to contain the final models
└── try-again1.ipynb    # notebook containing the model with highest accuracy for binary classification with and without half time results
```
### Setup Instructions

1. Create a virtual environment:
```bash
python -m venv venv
source venv/bin/activate  # On Windows: venv\Scripts\activate
```

2. Install dependencies:
```bash
pip install -r requirements.txt
```

3. Launch Jupyter:
```bash
jupyter notebook
```
