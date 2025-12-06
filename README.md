# AutoTagger — Flask User Interface

This is a Flask-based web application for running the AutoTagger Vehicle Parts Named Entity Recognition (NER) model locally.  
Users can type an automotive-style product listing (e.g., “2016 Toyota Corolla Brake Pads OEM”), and the system will extract:

- **MAKE**
- **MODEL**
- **YEAR**
- **PART**
- **BRAND**

The app loads the fine-tuned DistilBERT NER model exported from Kaggle and provides a simple demo interface for testing predictions.

---

## Project Folder Structure

Your project directory must be arranged exactly like this:

```bash
AUTO-TAGGER/
│
├── app.py
├── requirements.txt
│
├── autotagger-ner-model/
│   ├── config.json
│   ├── model.safetensors
│   ├── tokenizer.json
│   ├── tokenizer_config.json
│   ├── special_tokens_map.json
│   ├── vocab.txt
│   ├── training_args.bin
│
└── templates/
    └── index.html
```
---

## Create a Python Virtual Enviornment
```bash
python3 -m venv venv
source venv/bin/activate        # Linux/macOS
# OR
venv\Scripts\activate           # Windows
```

---
## Install all of the Needed Libraries
Install the needed libraries from the requirments.txt document

```bash 
pip install -r requirments.txt
```

---
### Run the program
```bash
python3 app.py 
```
navigate to the port that your terminal species in you browser example: localhost:3000

--- 
## Note: Model not inlcuded in this repo
Please not that the model has not been included in this repo because of storage limitations that github imposes. To get the model run the notbook included in the folder NER-model-implementation. Also the model is available on kaggle at the following Kaggle link. A fully ready version is available to the follwoing Google Drive link

Kaggle link: https://www.kaggle.com/code/elmerh14/auto-tagger

Google Drive link: https://drive.google.com/drive/folders/1uO1OI9CeFc4yaBvabXYzxnEdv1KtTqwR?usp=sharing
