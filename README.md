# Coriander-vs-Parsley Real-Time Classifier
Web application (📱 Mobile friendly) that uses a pre-trained NN model (MobileNet) in order to classify Coriander (Coriandre in French, قزبر in Moroccan dialect) and Parsley (Persil in French, معدنوس in Moroccan dialect).

@author: Abdelhamid ALAOUI

> Data is collected and provided by Ali Lakrakbi https://github.com/alilakrakbi/Coriander-vs-Parsley

📷 Dataset: 98 Parsley images and 150  Coriander images

🛠 Stack: p5.js, ml5.js, HTML/CSS and Javascript

* The deep learning model used for this purposes has been trained used Teachable machine, which uses Transfer Learning on the MobileNet model.
* The classification model is hosted freely on google servers.
* The web application is created using p5.js and hosted freely on p5js servers. 

**Important**: Data is not big and classes are unbalanced, this is a simple try/proof of concept with a pretrained model, I am sure there is a large margin of improvement through the use of class balancing, fine-tuning with deeper nets or just sampling (i.e: data augmentation) more from the parlsey class.
