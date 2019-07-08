# Dog Breed Classifier
This is a Jupyter notebook containing a deep learning project about Convolutional Neural Networks (CNN). 
A pipeline is built to process real-world, user-supplied images. Given an image of a dog, we will identify 
an estimate of the canine’s breed. If supplied an image of a human, the code will identify the resembling dog breed.

1.  Clone the repository and navigate to the downloaded folder.

	git clone https://github.com/amyllykoski/DogBreedClassifier
	cd DogBreedClassifier

2. Download the [dog dataset](https://s3-us-west-1.amazonaws.com/udacity-aind/dog-project/dogImages.zip). Unzip the folder and place it in the repo, at location path/to/dog-project/dogImages. The dogImages/ folder should contain 133 folders, each corresponding to a different dog breed.

3. Download the [human dataset](http://vis-www.cs.umass.edu/lfw/lfw.tgz). Unzip the folder and place it in the repo, at location path/to/dog-project/lfw. If you are using a Windows machine, you are encouraged to use 7zip to extract the folder.

4. Make sure you have already installed the necessary Python packages like so:

    pip install -r requirements.txt

Open a terminal window and navigate to the project folder. Open the notebook and follow the instructions.

	jupyter notebook dog_app.ipynb