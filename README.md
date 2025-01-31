Training Fruits Image Classification 
this is a machine learning project using tflite-support-nightly(TensorFlow lite to deploy our data and train it )
this project is to make a traning for our data to now or predict our data fruits here we git only some og samples that are in dataset.
this was created in google colab so we put the dataset.zip in a drive of class name Dataset 
and then we connect it to the google drive and make unzip for the dataset.
the dataset we trained it by use teachable machine 
then we get the data in dataset and make a train-data of 90% and remaining-data of 10%
then test-data make it 50% and the validation data is 50%
configure the model architecture to EFFICIENTNET_LITE2(make size of image 240*240 pixel and optimized on mobile )
we make the train by epochs=50, and we see that evry step of epochs the loss was decrease and the accuracy get increase this mean our work is will and then we make converstion to the path of train and download it 
then we convert it to tflite to use in mobile in future

