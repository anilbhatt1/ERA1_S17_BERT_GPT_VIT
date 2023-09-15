### BERT, GPT, VIT

**Objective** - To have a single transformer.py file that we can use to train all 3 models - BERT, GPT and ViT

#### src file details

- Folder : assignment
    - bert_data.py -> Data handling for BERT model
    - config.py -> Config file (not used)
    - config.yaml -> Yaml that stores model parameters
    - data_setup.py -> Data handling for VIT model (Pizza-Steak-Sushi images)
    - engine.py -> Utilities for ViT model including train
    - gpt_utils.py -> Utilities for GPT model
    - predictions.py -> Utilities for ViT model predictions
    - requirements.txt -> Requirements to be installed via PIP
    - transformer.py -> File that holds BERT, GPT and VIT models
    - vit_utils.py -> Utilities for ViT model like plotting, downloading images etc.
- Folder : course_docs
    - All the source files and notebooks provided by TSAI for this session
- Notebooks:
    - ERAV1_s17_BERT_v1.ipynb -> BERT model training. Same as course docs
    - ERAV1_s17_BERT_v2.ipynb -> BERT model training. Modularized
    - ERAV1_s17_BERT_v3.ipynb -> BERT model training. Driven through transformer.py and config.yaml from github
    - ERAV1_s17_GPT_v1.ipynb -> GPT model training. Same as course docs
    - ERAV1_s17_GPT_v2.ipynb -> GPT model training. Modularized
    - ERAV1_s17_GPT_v3.ipynb -> GPT model training. Driven through transformer.py and config.yaml from github
    - ERAV1_s17_ViT_v1.ipynb -> ViT model training. Same as course docs
    - ERAV1_s17_ViT_v2.ipynb -> ViT model training. Modularized
    - ERAV1_s17_ViT_v3.ipynb -> ViT model training. Driven through transformer.py and config.yaml from github