# Face Emotion Recognition
This project is a deep learning-based approach to face detection using Haar-cascade and emotion recognition based on facial expressions. It recognizes the person's emotion to one of the seven classes: neutral, sad, depressed, happy, surprised, feared, and disgust. The model is trained on the 
[FER-2013 dataset](https://www.kaggle.com/deadskull7/fer2013) using the MobileNetv2 architecture.

## Dataset
The [FER-2013 dataset](https://www.kaggle.com/deadskull7/fer2013) contains 35,887 grayscale images of faces labeled with one of the seven emotions. The images are 48x48 pixels in size.

## Methodology

The project consists of two main parts: face detection and emotion recognition. For face detection, we use Haar-cascade, which is a popular algorithm for detecting faces in images. For emotion recognition, we use a deep learning model based on the MobileNetv2 architecture. The model is trained on the FER-2013 dataset using Keras with TensorFlow backend.

## Results

The model achieved an accuracy of 94% on training set and 68% on the test set, which is competitive with other state-of-the-art models for emotion recognition.

<video width="640" height="360" controls autoplay loop>
  <source src="https://user-images.githubusercontent.com/63152481/220413757-3111d3d8-3fa3-4f5c-b767-ceff5038fdc1.webm">
</video>


## References

1. Viola, P., & Jones, M. (2001). Rapid Object Detection using a Boosted Cascade of Simple Features. Proceedings of the 2001 IEEE Computer Society Conference on Computer Vision and Pattern Recognition. CVPR 2001, 1, I-I. https://doi.org/10.1109/cvpr.2001.990517
2. Sandler, M., Howard, A., Zhu, M., Zhmoginov, A., & Chen, L.-C. (2018). MobileNetV2: Inverted Residuals and Linear Bottlenecks. Proceedings of the IEEE Conference on Computer Vision and Pattern Recognition, 4510–4520. https://doi.org/10.1109/cvpr.2018.00927
