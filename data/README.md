# Dataset of JPEG Mineral Images For Silver Classification.
### Orginal Silver Image Dataset: 
Silver Images: 16,695   
Non-silver Images: 3,869                              
[https://drive.google.com/drive/folders/silver_detection/dataset](https://drive.google.com/drive/folders/143MnLPbHyAF5aqPPYWIergjl5NX1t0vO)

   
### Cleaned and Balanced Silver Mineral Image Dataset 
Silver Images: 3,655   
Non-silver Images: 3,655     
[https://drive.google.com/drive/folders/silver_detection/cleaned_dataset](https://drive.google.com/drive/folders/1VoTjm4lIN6GQ2r1tS52o9DGcBkNzQaFO)


## Data
Images were collected from the Mindat.org database and organized into two binary classes for classification: silver and non_silver. The silver_images folder contains 3,869 JPEG images, and the non_silver_images folder contains 16,695 JPEG images. All image data are stored on Google OneDrive, and the data folder provides a direct link from the README.md file. The folder structure of the Google OneDrive is shown below.Two versions of the dataset are provided. The first is the original downloaded dataset. The second is a cleaned and balanced dataset prepared for machine learning.

### Orginal Silver Image Dataset
<img width="517" height="258" alt="image" src="https://github.com/user-attachments/assets/fa95db72-092e-425e-aef7-c81316a17889" /> <br>

### Cleaned and Balanced Silver Mineral Image Dataset
<img width="612" height="245" alt="image" src="https://github.com/user-attachments/assets/1fea60e0-42f7-4296-9766-63cd80de31ac" /> <br>


The silver class includes native silver and related silver-bearing minerals identified with the following keywords. A image distribution is not currently listed:

- *Silver*
- *Argentum*
- *Argentite*
- *Chlorargyrite*
- *Chalcopyrite*
- *Proustite*
- *Pyrargyrite*
- *Stephanite*
- *Polybasite*
- *Pearceite*
- *Miargyrite*
- *Freibergite*

The non-silver class is composed of approximately 70% hard negative images and 30% easy negative images to improve model robustness. The images are identified using the following keywords:

- *Galena*
- *Pyrite*
- *Hematite*
- *Graphite*
- *Stibnite*
- *Chalcopyrite*
- *Molybdenite*

Each image has corresponding metadata that provides a class label of 1 for silver and 0 for non-silver, along with the associated mineral name, which can be used directly in machine learning classification models. Each datasethas it own metadata file for each of its silver and non-silver class.

**Note:** All other CSV and JSON files in the data folder can be ignored, as they are archived files used during the creation of the image dataset.





