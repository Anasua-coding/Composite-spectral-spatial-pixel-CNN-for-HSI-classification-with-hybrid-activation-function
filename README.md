# Composite-spectral-spatial-pixel-CNN-for-HSI-classification-with-hybrid-activation-function
# DATA SOURCE
Link: http://www.ehu.eus/ccwintco/index.php/Hyperspectral_Remote_Sensing_Scenes
# Here, a noble Composite Spectral Spatial Pixel CNN model for the classification of hyperspectral data is presented which is an amalgamation of 3D-2D-1D CNN. While the 3D and 2D CNN exploit the spectral-spatial features effectively, 1D CNN works on pixel-wise feature extraction.
# How to execute our code
At first we need to import some libraries of Google credentials.
After that we have to get the permission granted from the Gmail account to access any files from the Google Drive. Then we need to copy that generated link from the Gmail account and paste it on google colab.
Each and every file has a unique id and that id can be obtained from google drive. If we want to have an access to a particular data set we need to copy that id from google drive and subsequently paste it on google colab.
In the next phase we have defined some functions like split of training testing ratio, dimension reduction technique and creating image cubes.
After that we have to fix some hyperparameters namely window size; number of bands; training ratio and testing ratio.
Afterwards we trained our ResnetConvLstm model.
Finally we obtained the accuracy of our model and to visualize the predicted image and the ground truth image of that data set.

# Please Cite:
# Banerjee, A., Swain, S., Rout, M. et al. Composite spectral spatial pixel CNN for land-use hyperspectral image classification with hybrid activation function. Multimed Tools Appl (2024). https://doi.org/10.1007/s11042-024-19327-0

