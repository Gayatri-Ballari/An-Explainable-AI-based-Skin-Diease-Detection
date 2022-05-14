# An-Explainable-AI-based-Skin-Diease-Detection
Automated detection of Skin disease using deep learning technique and provide Explain-ability technique to help us better understands our model's predictions, and how we could further improve its performance.


Convolutional Neural Network (CNN) models have been highly successful in solving complex
vision based problems. However, deep models are perceived as &quot;black box&quot; methods considering
the lack of understanding of their internal functioning. There has been a significant recent
interest to develop explainable deep learning models. Building on a recently proposed method
called SHAP and Grad-CAM, we propose both the models to provide better visual explanations
of CNN model predictions (when compared to Grad-CAM), in terms of better localization of
objects as well as explaining occurrences of multiple objects of a class in a single image. In this
work, a baseline ResNet50 will be trained, evaluate the model, and use SHAP model
explainability technique to help us better understand our model&#39;s predictions, and how we could
further improve its performance. SHAP (Shapley Additive explanation) to explain the output of
any machine learning model. It connects optimal credit allocation with local explanations using
the classic Shapley values from the related extensions. We provide a mathematical explanation
for the proposed method, Grad-CAM which uses a weighted combination of the positive partial
derivatives of the last convolutional layer feature maps with respect to a specific class score as
weights to generate a visual explanation for the class label under consideration. Our extensive
experiments and evaluations, both subjective and objective, on standard datasets showed that
Grad-CAM indeed provides better visual explanations for a given CNN architecture when
compared to SHAP.


The model was able to successfully extract feature from the dataset. The results obtained with deep learning based Resnet-50 model is of 91.62%. 
The output of SHAP and GRAD CAM is a list of explanations, reflecting the contribution of each feature to the prediction of a data sample.
On Comparing the SHAP and GRAD CAM results the gradcam gives the better explanation than SHAP model.

