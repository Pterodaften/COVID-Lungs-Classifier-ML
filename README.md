# COVID-Lungs-Classifier-ML
Dataset of normal and COVID (+bacterial infection) lungs, obtained from https://www.kaggle.com/praveengovi/coronahack-chest-xraydataset

My attempt of building an ML classifier using Efficient Net 7 with custom modifications, untested due to enormous computational demands of the net and the size of the data. Was not so efficient net after all... 
5910 images in total, which were then additionally augmented. 

#Model parameters
batch_size=64
img_width, img_height, img_num_channels=224,224,3
epochs=15

loss='binary_crossentropy', optimizer='adam', metrics=['accuracy'])

