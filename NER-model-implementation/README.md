# AutoTagger — Vehicle Parts Named Entity Recognition (NER)

AutoTagger is a DistilBERT-based Named Entity Recognition (NER) system designed to automatically extract automotive attributes from product listing titles.  
It identifies the following entities:

- **MAKE**
- **MODEL**
- **YEAR**
- **PART**
- **BRAND**



---

## Running the Notebook Locally

### 1. Create a Python virtual environment


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

## Run the Notebook on Kaggle
The model was trained on kaggles platform and is public and can be accesed at the following link. 

https://www.kaggle.com/code/elmerh14/auto-tagger