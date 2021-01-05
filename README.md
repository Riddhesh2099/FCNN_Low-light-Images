# FCNN_Low-light-Images
Fully Convolutional Network which allows the user to extract data and get a well-lit output of an input low-light dark image
Run the driver notebook
<ol>
<li> System Requirements
	<ul>
	<li><t>&ensp;&ensp;● TensorFlow 1.15
	<li><t>&ensp;&ensp;● Rawpy
	<li><t>&ensp;&ensp;● Scipy 1.2.0
	</ul>
<li> To run put train_Sony.py, test_Sony.py and NNFL_Driver_Colab.ipynb in the same Directory
<li> Edit the dataset path in both .py files according to your need.
<li> The naming convention of dataset files (Contact owner for dataset)
	<ul>
	<li>&ensp;&ensp;● Starting with “0” for Training Data (230 Unique images)
	<li>&ensp;&ensp;● Starting with “1” for Testing Data (50 unique images)
	<li>&ensp;&ensp;● The last 4 digits indicate the exposure time for each image
	</ul>
<li> On Colab we can’t get more than 100 images for training.
<li>Train_Sony.py will keep saving the trained model in output in Results_Sony Folder as given saving Frequency With the Number of total epoch till that point as a folder name.
<li>test_Sony will save all output of test data in Result/final. Images names will contain epoch number of each saved epoch at saving frequency.
</ol>
<b>Further Instructions are in NNFL_Driver_Colab.ipynb file
