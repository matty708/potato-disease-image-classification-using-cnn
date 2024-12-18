# potato-disease-image-classification-using-cnn
This is a deep learning project aimed at classifying potato leaf health using Convolutional Neural Networks (CNNs). The model processes images from the PlantVillage dataset to identify three categories:
•	Potato___Healthy: Leaves without any disease.
•	Potato___Early_Blight: Leaves exhibiting initial symptoms of blight disease.
•	Potato___Late_Blight: Leaves affected by advanced stages of blight disease.





Key Features:
•	Data Augmentation: Improves model generalization by applying random flips and rotations to the training images.
•	Preprocessing: Includes resizing and normalization of input images to prepare the dataset for training.
•	Model Architecture: Custom CNN design with multiple convolutional and pooling layers for accurate classification.
•	Performance Metrics: Tracks accuracy and loss during training and validation to ensure optimal performance.
•	Model Saving: Automatically saves trained models with versioning using TensorFlow’s SavedModel format.
Tools and Libraries:
•	TensorFlow/Keras: For creating and training the CNN model.
•	Python: For scripting and implementing the project workflow.
•	Google Colab: For GPU-accelerated training and experimentation.
Usage:
This project helps detect potato leaf diseases, providing a useful tool for farmers to identify and prevent crop health issues early. The methodology and model can be adapted for other plant diseases using similar datasets.
