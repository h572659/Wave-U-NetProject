# Wave-U-NetProject
An attempt at implementing a version of Wave-U-Net for the purpous of denoising sound files.
Using the model:
![image](https://github.com/user-attachments/assets/fd23e123-c593-421b-9a1a-5018028ad707)
Unfortunatly I have not had the time to implement a good way to use the model that does not require a bit of legwork for you.
Other better ways are no doubt also available.
You will find this code at the bottom of the notebook.

The notebook is otherwise usable in Google Colab, though you would obviously need to get the training data yourself and make the 
necessary changes to access the files from google drive and so on.

Data:
This must be converted from mp3 to wav:
https://commonvoice.mozilla.org/en/datasets Norwegian Dataset Nynorsk Common Voice Corpus 21.0

Noise:
https://www.kaggle.com/datasets/chrisfilo/demand
https://zenodo.org/records/6687982

v3 of the trained models were too big to include directly here, so here is a link:
https://huggingface.co/JonRon/Denoiser/blob/main/waveunet_v3.keras
