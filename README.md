This project uses **TensorFlow 2.15.0** and leverages a deep learning model based on **DenseNet121** to detect lymphoma, a blood cancer type, from medical images. The architecture includes a DenseNet121 backbone with custom layers for fine-tuning, incorporating **Global Average Pooling**, **Dense layers** with **L2 regularization**, and **Dropout** for robust performance. 
The model is trained using **Adam optimizer** and `categorical_crossentropy` loss, with **EarlyStopping** to prevent overfitting. **ImageDataGenerator** is used for data augmentation, enhancing model generalization. Training and validation metrics are visualized to track model progress, and the final model is saved for future use.
