## Exploring Dimensionality Reduction Techniques

This mini-project investigates the impact of various dimensionality reduction techniques on the performance of Support Vector Machines (SVM). The project begins by implementing and comparing t-SNE, PCA, and LDA to reduce the dimensionality of the dataset while retaining critical information. These techniques are essential for understanding how reduced dimensions affect model performance and for visualizing the data distribution. By applying these methods, we aim to enhance the efficiency and interpretability of the SVM models.

## Implementing and Evaluating SVM Models

The second phase of the project focuses on the implementation and evaluation of SVM models using both linear and polynomial kernels. We compare a custom-built polynomial SVM with the scikit-learn library implementation for polynomial degrees ranging from 1 to 10. This includes applying SVM to the Iris dataset, analyzing performance using different kernels and dimensionality reduction techniques, and visualizing decision boundaries. Additionally, a custom SVM algorithm is implemented from scratch to compare its performance against the scikit-learn version, providing a deeper understanding of the underlying mechanics of SVMs.

## Enhancing Model Performance with Autoencoders and SMOTE

The final part of the project addresses data denoising and class imbalance using autoencoders and SMOTE (Synthetic Minority Over-sampling Technique). These methods are applied to the highly imbalanced credit card fraud detection dataset to improve model performance. By using autoencoders for data denoising and SMOTE to balance the classes, we demonstrate significant improvements in model accuracy and robustness. This section also includes the implementation of a Generalized Multiclass Support Vector Machine (GenSVM) and its comparison with traditional SVMs, providing comprehensive insights into advanced machine learning techniques for real-world applications.

