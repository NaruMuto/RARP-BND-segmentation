# RARP-BND-segmentation
Code of deep learning segmentation model for bladder neck dissection  during robot-assisted radical prostatectomy (RARP).

This repository provides implementation of UNet, UNet++, DeepLabv3+ models. 

The **base model** demonstrated in our manuscript is provided as `ZEUS_Basel.h5`.  
In addition, prototype and final models obtained via active learning are included.

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
