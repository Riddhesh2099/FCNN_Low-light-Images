# FCNN_Low-light-Images
Fully Convolutional Network which allows the user to extract data and get a well-lit output of an input low-light dark image
Run the driver notebook
<list>
<li>1. System Requirements
	<list>
	<li><t>&ensp;&ensp;● TensorFlow 1.15
	<li><t>&ensp;&ensp;● Rawpy
	<li><t>&ensp;&ensp;● Scipy 1.2.0
	</list>
<li>2. To run put train_Sony.py, test_Sony.py and NNFL_Driver_Colab.ipynb in the same Directory
<li>3. Edit the dataset path in both .py files according to your need.
<li>4. The naming convention of dataset files (Contact owner for dataset)
	<list>
	<li>&ensp;&ensp;● Starting with “0” for Training Data (230 Unique images)
	<li>&ensp;&ensp;● Starting with “1” for Testing Data (50 unique images)
	<li>&ensp;&ensp;● The last 4 digits indicate the exposure time for each image
	</list>
<li>5. On Colab we can’t get more than 100 images for training.
<li>6. Train_Sony.py will keep saving the trained model in output in Results_Sony Folder as given saving Frequency With the Number of total epoch till that point as a folder name.
<li>7. test_Sony will save all output of test data in Result/final. Images names will contain epoch number of each saved epoch at saving frequency.
</list>
<b>Further Instructions are in NNFL_Driver_Colab.ipynb file
