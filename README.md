# Flowchart Shapes and Arrow Direction Detection & OCR

## Project Description
This project aims to detect the basic shapes of flowcharts, determine arrow directions, and perform Optical Character Recognition (OCR) on the text within the flowchart images.

## Procedure
1. **Data Collection**: Obtained a dataset comprising 774 hand-drawn flowchart images from an online repository.
2. **Annotation**: Utilized [makesense.ai](https://www.makesense.ai/), an online annotation tool, to annotate the images according to the YOLO format.
3. **Data Preparation**: Split the dataset into training and validation subsets.
4. **Data Configuration**: A data.yaml file will be created to configure the training process where the paths to the training, validation and test datasets will be specified. 
5. **Model Development**: Developed a custom model using YOLOv8 Nano architecture to detect shapes, arrow directions, and perform OCR.
6. **Training**: Trained the model using the annotated dataset.
7. **Validation**: Conducted validation procedures to assess the model's performance and fine-tune as necessary.
8. **Testing**: Employed the YOLOv8 predict function to evaluate the model's performance on unseen data, ensuring unbiased evaluation.

## Project Dataset
[Dataset Link](https://drive.google.com/drive/folders/1l53uKhMYAUouLWVcWNZrBVAg4sTHU8M9?usp=sharing)

## Run on Colab
The project was executed on Google Colab. For detailed implementation and execution, refer to the following Colab notebook:
[Google Colab Notebook](https://colab.research.google.com/drive/1MZURLsx8bAbFS_EDGozx67H2d5h5QTGH#scrollTo=hIEB_S45Rh8e)

## Demo
  * Shapes and Arrow Direction Detection Results
    
    ![res](https://github.com/NagaNarveen30/internship_projects/assets/121602385/092e937c-e85b-4167-9a36-64fb1d1194d9)

  * OCR Results
    
    ![resocr](https://github.com/NagaNarveen30/internship_projects/assets/121602385/5a3888fb-179a-49a9-a364-71a3efa62a37)
