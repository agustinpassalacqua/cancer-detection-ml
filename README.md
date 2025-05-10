ENGLISH BELOW 

# cancer-detection-ml
Modelo de Machine Learning de clasificacion binaria para detectar cáncer de mama usando el Breast Cancer Wisconsin Dataset.


## 🔍 Dataset
- [Link del dataset en Kaggle](https://www.kaggle.com/datasets/uciml/breast-cancer-wisconsin-data)
- Las características se calculan a partir de imágenes digitalizadas de aspirados con aguja fina (FNA) de masas mamarias.

## 🧠 Modelos testeados
- Support Vector Machine (SVM)
- K-Vecinos más Cercanos (KNN)
- Árbol de Decisión binario
- Random Forest
- Naive Bayes
- Linear Discriminant Analysis (LDA)

## 🏆 Performance
Evaluado con validación cruzada y un conjunto de prueba independiente
- Mejor AUC-ROC en desarollo: 0.995 usando SVM con kernel lineal
- AUC-ROC en validacion: 0.939
- Recall en validacion: 0.905


## ✅ Conclusión
SVM ofreció una excelente capacidad de generalización sobre datos no vistos. Por los buenos resultados obtenidos en SVM y LDA, el problema de detectar cancer bajo estos atributos pareceria ser linealmente separable. El mejor modelo detecta aproximadamente 9 de 10 casos positivos, evitando el error de tipo II (Falsos Negativos) el 90% de las veces.

## 📁 Files
- `cancer_detection_model.ipynb`: notebook principal con el código, análisis y resultados

################################################################################

# Breast Cancer Detection with Machine Learning

This project uses the Breast Cancer Wisconsin Diagnostic dataset to train several ML models for binary classification.

## 🔍 Dataset
- [Link to dataset on Kaggle](https://www.kaggle.com/datasets/uciml/breast-cancer-wisconsin-data)
- Features are computed from digitized images of fine needle aspirates (FNA) of breast masses.

## 🧠 Models Tested
- Support Vector Machine (SVM)
- K-Nearest Neighbors (KNN)
- Decision Tree
- Random Forest
- Naive Bayes
- Linear Discriminant Analysis (LDA)

## 🏆 Performance
Evaluated with cross-validation and an independent test set:
- Best AUC-ROC in development: 0.995 using SVM with a linear kernel
- AUC-ROC in validation: 0.939
- Recall in validation: 0.905

## ✅ Conclusion
SVM demonstrated excellent generalization ability on held-out data. Based on the strong results from both SVM and LDA, the problem of detecting cancer with these features appears to be linearly separable. The best model detects approximately 9 out of 10 positive cases, successfully avoiding Type II errors (False Negatives) 90% of the time.

## 📁 Files
- `cancer_detection_model.ipynb`: main notebook with code, analysis, and results
