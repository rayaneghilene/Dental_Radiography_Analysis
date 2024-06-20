# Analysis of Dental Radiography dataset with CNN
This repository contains code for training a PyTorch Lightning model to classify images from a dental radiography dataset. The model not only predicts the class label but also performs bounding box regression using a custom dataset.

The dataset consists of dental radiography images along with annotations for class labels and bounding box coordinates.

Here's an example of what the model does

![image](https://github.com/rayaneghilene/Dental_Radiography_Analysis/blob/main/testimage.png)

## Usage
### 1. Clone the repository:
```bash
git clone https://github.com/rayaneghilene/Dental_Radiography_Analysis.git
cd Dental_Radiography_Analysis
```

### 2. Create a virtual environment (optional but recommended):
```bash
python -m venv venv
source venv/bin/activate  # On Windows use `venv\Scripts\activate`
```

### 3. Install the required dependencies:
```python
pip install -r requirements.txt
```


## Citation

The dataset used for this project can be found at the following [link](https://www.kaggle.com/datasets/imtkaggleteam/dental-radiography?resource=download)

The dataset is organized into three main folders: train, valid, and test. Each folder contains JPEG images and an _annotations.csv file with annotations for each image. The CSV files have the following columns:

- **filename**: Name of the image file
- **width**, **height**: Dimensions of the image
- **class**: Class label of the image
- **xmin, ymin, xmax, ymax**: Bounding box coordinates (for one bounding box per image)


## Contributing
We welcome contributions from the community to enhance work. 
If you have ideas for features, improvements, or bug fixes, please submit a pull request or open an issue on GitHub.


## Support
For any questions, issues, or feedback, please reach out to rayane.ghilene@ensea.fr