# Fine_Tuned_VGG16-for-Image-Classification

Made use of VGG16 model and fine-tuned it to fit the dogs_vs_cats image dataset.
Made use of GlobalMaxPooling instead of Flatten and Dense Layers at the end of the convolution blocks. Significant drop in number of parameters
~138 Million Parameters ---> ~15 Million Parameters,thereby reduction in Computational time and load but still retaining the accuracy of the original model as convolutional layers contribute to most of the learning in CNNs and none of the convolutional layers were removed. 

#Used flask and html to make a web application. 
    Learnt how to create a web application to hold said model and perform image classification.
checkout :DeepLizard Blog
