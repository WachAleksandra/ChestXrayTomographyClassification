# ChestXrayTomographyClassification
This repository contains a master’s thesis project focused on applying deep learning techniques for the classification of medical images, specifically chest X-rays (RTG) and CT scans, for detecting lung diseases such as pneumonia and lung cancer.

📌 **Project Overview**

The goal of this project is to evaluate and compare the performance of different deep learning architectures in medical image classification tasks. The models were trained to automatically identify pathological conditions in medical imaging data.

The following architectures were analyzed:

- CNN (custom convolutional neural network)
- VGG16
- Xception
- EfficientNetB3

🧪 **Experiments**

The models were tested on two classification tasks:

- Pneumonia detection from chest X-ray images
- Lung cancer detection from CT scans

Key aspect of the experiments:

- Impact of the patience hyperparameter (values: 3, 5, 10) on training performance and generalization

Each model was evaluated using:

- Accuracy
- Loss
- Precision / Recall (depending on implementation)
- Performance on training, validation, and test sets

📊 **Key Findings**

- VGG16 achieved the most stable and consistent results across both tasks.
- Xception also performed well, with competitive accuracy.
- The custom CNN showed unstable performance but remained functional.
- EfficientNetB3 struggled with both datasets and required further tuning.

Lower patience values (3–5) often helped prevent overfitting and improved generalization in some cases.

🧠 **Conclusion**

The experiments show that deep learning models can effectively support the classification of medical images, such as chest X-rays and CT scans, for detecting pneumonia and lung cancer. The results confirm that properly configured neural networks are able to learn relevant diagnostic features from imaging data.

A significant factor influencing model performance was the patience parameter, which affected training duration and generalization ability. In many cases, lower values (3–5) helped achieve more stable results and reduced overfitting.

Among the tested architectures, VGG16 provided the most consistent and reliable performance, while Xception also achieved strong results. The custom CNN showed more variability depending on the configuration, and EfficientNetB3 performed less effectively on the tested datasets.

Overall, the study highlights the importance of both architecture selection and hyperparameter tuning in medical image classification tasks, confirming the potential of deep learning in supporting medical diagnostics.

⚙️ **Technologies**
- Python
- TensorFlow / Keras
- NumPy, Pandas
- Matplotlib / Seaborn
- Jupyter Notebook
