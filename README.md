# DogSorter
This is a project for "Fundamentos de los Sistemas Inteligentes" which consist in a program made in Python that class 9 different breeds:
* Chihuahua
* Shih-Tzu
* German Shepherd 
* Siberian Husky
* Beagle
* English Foxhound
* Bull Mastiff
* Staffordshire Bullterrier
* French Bulldog

I have used [Stanford Dogs Datset](https://www.kaggle.com/jessicali9530/stanford-dogs-dataset), where I get 1532 images of the different breeds, I choose the VGG16 model where I changed the input shape and remove the fully connected layer and I add a different one with a couple dense layers along with some Dropout layers.
