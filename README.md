# Face-Detection-and-Analysis-with-LFW-Dataset

**Face Detection and Analysis with LFW Dataset** : https://www.kaggle.com/datasets/jessicali9530/lfw-dataset/code?datasetId=26922&sortBy=dateRun&tab=profile&excludeNonAccessedDatasources=false

![1](https://github.com/TITHI-KHAN/Face-Detection-and-Analysis-with-LFW-Dataset/assets/65033964/bf008641-9af0-4eec-abe4-5c29e3a4e69c)

![2](https://github.com/TITHI-KHAN/Face-Detection-and-Analysis-with-LFW-Dataset/assets/65033964/1cc74abf-37d1-4388-88be-efebb196c466)

## Let's break down the code step by step:

1. **Ignoring Warnings and Importing Libraries:**
   - The code starts by ignoring any warnings using `warnings.filterwarnings('ignore')` for cleaner output.
   - It imports necessary libraries including `os`, `random`, `PIL` (Python Imaging Library) for image processing, `matplotlib` for plotting, and `numpy`.

2. **Setting up Dataset Directory:**
   - The dataset directory path is defined as `data_dir_path`.
   - If the directory doesn't exist, it's created using `os.makedirs(data_dir_path, exist_ok=True)`.

3. **Selecting Random Person:**
   - It lists all the directories (each representing a person) in the images directory.
   - Then, it randomly selects one person from the list.

4. **Selecting Random Images of the Person:**
   - It selects a few random images (here, 5) of the randomly selected person.
   - These images will be used for further analysis.

5. **Extracting Image Properties:**
   - For each selected image, it extracts properties like name, size, and format using the PIL library.

6. **Selecting Random Images of Random Persons:**
   - It randomly selects 5 persons from the dataset.
   - For each person, it selects one random image.
   - These images will be used for visualization.

7. **Displaying Selected Images:**
   - It plots the selected images of the random person for visualization.

8. **Further Processing and Visualization:**
   - It imports additional libraries (`pandas` for data analysis and `cv2` for computer vision tasks).
   - It reads metadata about the dataset and plots a histogram showing the distribution of the number of images per person.
   - It displays summary statistics about the number of images per person.
   - It loads an example image, converts it to grayscale, and performs face detection using the Haar Cascade classifier.
   - It draws bounding boxes around detected faces and displays the result.
   - It plots images of random persons with bounding boxes around detected faces for visualization.

Overall, this code demonstrates various tasks such as dataset setup, image selection, data analysis, and face detection using the LFW dataset. It provides insights into working with image datasets and performing basic computer vision tasks.
