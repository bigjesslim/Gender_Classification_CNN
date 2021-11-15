# Gender_Classification_CNN

Constructed a CNN to classify gender based on the Adience dataset retrieved from: https://talhassner.github.io/home/projects/Adience/Adience-data.html#agegender

Techniques used: 
* Transfer Learning and fine-tuning (with pre-trained models from Keras)
* Data Augmentation (geometric, photometric and noise injection methods) 
* Test Set Oversampling (i.e., predicting test images using different crops) 

Final model: Fine-tuned DenseNet-169 Transfer Learning Model + Photometric Data Augmentation + Test Set Oversampling
Maximum accuracy acheived: 91.23%

Credits go towards group members Daniel and Liang Yi, who worked on this project together with me. 
