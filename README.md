# RARP-BND-segmentation
Code of deep learning segmentation model for bladder neck dissection  during robot-assisted radical prostatectomy (RARP).

This repository provides implementation of UNet, UNet++, DeepLabv3+ models. 

The following trained models are provided:

- `ZEUS_base.h5` : Base model demonstrated in the manuscript
- `ZEUS_prototype.h5` : Prototype model obtained after the first step active learning
- `ZEUS_final.h5` : Final model obtained after the second step active learning

---

## Related Publication
This code is associated with the manuscript:  
**"[Deep-Learning Segmentation to Guide Bladder Neck Dissection in Robot-Assisted Radical Prostatectomy]"**  
[Journal name], [Year].  
DOI: [Insert DOI here]

---

## Data Availability
Due to patient confidentiality, the operative video dataset cannot be shared publicly.  
Annotated samples are not available.  
The code here allows model construction, training, evaluation, and active learning 
using your own dataset with the same directory structure.

---

## Requirements

This project is tested on **Google Colab**.  
If you use Colab, please run the setup cells in each notebook:

```python
from google.colab import drive
drive.mount('/content/drive')

!pip install -r requirements.txt
