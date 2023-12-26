Plant Disease Detection using Fuzzy KNN and MLP


->Requirements:-

To run this project, you will need the following Python packages:

numpy
scikit-learn
tensorflow
keras
opencv-python
matplotlib

->You can install these packages using pip by running the following command:

  pip install numpy scikit-learn tensorflow keras opencv-python matplotlib
  

->Usage

To use this project, follow these steps:
1. Download the PlantVillage dataset from Kaggle and extract it to the data directory.
2. Open Jupyter Notebook by running the following command in your terminal:
				```
				jupyter notebook
				```	
3. Navigate to the plant-disease-classification directory in Jupyter Notebook.
4. Open the Fuzzy KNN & MLP.ipynb notebook and modify the data_dir variable to point to the data[if not any([x in directory for x in ["Apple"]]):] and we can also add any leaf name instered of apple for example[if not any([x in directory for x in ["Apple", "Grape", Potato]]):] and we can execute. I only added one leaf name apple because the processing time is taking to long if i take multipul names at a time.

5. Run the ipynb notebook to train the MLP & Fuzzy KNN model on the data.
6. In the real time testing we have add the link path as a input image then we hit run and program will display the output image.

