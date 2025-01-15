# DeepLearning_Xray_analysis
### This Deep Learning project's objective is  The classification of Chest X-ray images into Healthy\Viral pneumonia\Bacterial pneumonia.
### This was done by building deep neural networks, and using different classification methods like KNN,t-SNE, and Anomaly Detection methods.
<img src="https://github.com/user-attachments/assets/af1f71ce-b88a-4b85-8951-316c28ebaef5" alt="person128_bacteria_606" width="200" height="150">





Running the notebook:

In Tests.ipynb file, add the following paths in order to run the code:

1) first- download all files from https://drive.google.com/drive/folders/1EDQvw4aLsWWPMs58YKzbwHm2Bnvhp4mi?usp=sharing to your google drive.
this link has all trained weights of the models in this project.
nest.
2) in Load trained models weights- change FILENAME to folder name in googldrive to wich you downloaded the weights.

3) part 1.1: path_to_binary_test_dir = "insert/your/path"- add the path to the test files you want to test the model  on

4) part 1.1: bin_weights_path = 'path/in/your/drive/to/binary_model_weights.h5':
add path to file 'binary_model_weights.h5', that was trained by us, and was given in the google drive link to all trained weights.

5) part 1.1: 
image_path ="path/to/your/image.jpg"
for classifying a new image, add a path to the image.

6) part 1.2: path_to_categorial_test_dir = "insert/your/path"- add the path to the test files you want to test the model  on

7) part 1.2: cat_weights_path = "your_path/categorial_model_weights.h5"
add the path to the trained weights file named: 'model_weights_transfer_part2.h5'
8) part 1.2: 
image_path ="path/to/your/image.jpg"
for classifying a new image, add a path to the image.

9) part 2: path_to_binary_test_dir = #"insert/your/path" - path to test files for the binary model

10) part 2: path_to_categorial_test_dir = #"insert/your/path"- path to test files for categorial model

11) part 2: trained_binary_knn_model = "insert_your_path/binary_knn_model.pkl"= insert the path to the file of trained knn weights, by the name of- 'binary_knn_model.pkl' from the google drive link given at the top.

12) part 2: trained_categorial_knn_model ='/content/deepLearningProj/categorial_knn_model.pkl"- path to trained knn weigths for the categorial model, by the name of 'categorial_knn_model.pkl', found in the google drive link

13) part 3: autoencoder_trained_weights = '/path/to/aoutoencoder/weights/from/your/drive'
add thrained weights file by the name of 'autoencoder_model.h5', found in the google drive link given

14) part 3:

# Define directory paths
test_normal_dir = 'your/path/to/test/file/of/healthy/images'
test_pneumonia_dir = 'your/path/to/test/file/of/sick/images'
add paths to test/NORMAL
and to tests/PNEUMONIA

15) part 3: new_image_path =  #"path/to/your/new/image.jpg"
add path to image you want to categorize

16) part 4: sick_images_dir = "insert/your/path_to_sick_images"
	normal_images_dir = "insert/your/path_to_normal_images"
