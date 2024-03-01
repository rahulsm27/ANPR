# Automatic Number Plate Recognition (ANPR) system using YOLO (You Only Look Once) 

## The repo demonstrates how we can use YOLO model to detect a license plate in a video


1. Data Collection: Gather a large dataset of images containing vehicles with number plates. 

2. Data Annotation: Annotate the dataset to mark the bounding boxes around the number plates. 

3. Preprocessing: Preprocess the images and annotations as required. This might involve resizing, normalization, and data augmentation techniques to improve the model's robustness.

4. Model Selection: Choose a YOLO variant suitable for your task. I have selected YOLO NAS

5. Model Training: Train the chosen YOLO model on your annotated dataset. This involves feeding the images and their corresponding annotations into the model and adjusting its weights to minimize the detection errors.

6. Evaluation: Evaluate the trained model on a separate validation dataset to assess its performance metrics such as precision, recall, and mean average precision (mAP).

7. Integration with ANPR Logic: Once you have a YOLO model that can accurately detect number plates, integrate it with the ANPR logic. This involves extracting the detected number plate regions and processing them to recognize the alphanumeric characters using OpenCV library.

8. Character Recognition: Implemented OCR (Optical Character Recognition) techniques to recognize the characters on the number plate. We can use libraries like Tesseract or implement our custom OCR solution depending on your requirements.

