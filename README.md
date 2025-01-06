# music-genre-classification
An automated system for music genre classification using machine learning and deep learning models.

Instructions for Running the Project

Prerequisites
- A Google account to use Google Colab.
- A Kaggle account to download the dataset.
- Basic familiarity with Jupyter Notebook or Google Colab.



Steps to Run the Code
1. Open the Project File:
   - Download the `.ipynb` file provided as a secondary resource submission.
   - Open it in Google Colab for an optimal experience.

2. Download the Dataset:
   - Download the dataset from this Kaggle link (https://www.kaggle.com/datasets/andradaolteanu/gtzan-dataset-music-genre-classification) or Google Drive (https://drive.google.com/file/d/15KGC44W83vRvrx8oZpmA982WMEwy4oiV/view) which is as a ZIP file.

3. Upload the Dataset to Google Drive:
   - Extract the downloaded ZIP file.
   - Upload the `genres_original` folder (or equivalent) to a directory in your Google Drive.

4. Connect Google Drive to Colab:
   - You can use the following code snippet in Colab to connect your Google Drive:
  
     from google.colab import drive
     drive.mount('/content/drive')
     
   - Locate the path to your uploaded dataset in Google Drive.

5. Update the `data_path` Variable:
   - Navigate to the `genres_original` folder in Google Drive, right-click to copy the path, and replace the placeholder in the first code cell:
    
     data_path = "/content/drive/MyDrive/<your_path_to_genres_original>"
     

6.Run the Code Systematically:
   - Start from the first code cell and execute each cell in order.
   - Ensure no errors occur; if you encounter any, verify the dataset path and prerequisites.



Output
- The notebook will generate:
  - Accuracy metrics for Random Forest, SVM, MLP, CNN, and LSTM models.
  - Visualizations such as training accuracy curves and confusion matrices.
  - Exported models and evaluation results in designated files.


Additional Notes
- For better performance, consider running this project on a GPU-enabled environment in Colab. Go to **Runtime > Change Runtime Type > Hardware Accelerator > GPU**.
- Ensure the required Python libraries are installed (e.g., TensorFlow, librosa, sklearn, etc.), as they are critical for the project.

