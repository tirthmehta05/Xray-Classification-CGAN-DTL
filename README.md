# Xray-Classification-CGAN-DTL
Implementation of the Classification of X-ray images into COVID-19, pneumonia, and TB using cGAN and fine-tuned deep transfer learning models research paper.
<ul>
<li><b>Purpose:</b> The rapid increase in the spread of the coronavirus disease of 2019 (COVID19) has led to a need for reliable, effective, and readily available testing on a large scale. While diagnostic testing has been a support to public health, newer technology can be used to provide low-cost and convenient test options for patients. X-ray scanning can be performed to resolve this issue and produce quicker and more precise results. Currently, a radiologist is required to examine these X-ray images. However, deep convolutional neural networks can also be used to perform X-ray examinations and employed for the detection of COVID-19. We propose a Conditional Generative Adversarial Network (cGAN) with a fine-tuned deep transfer learning model to classify chest X-rays into six categories: COVID-Mild, COVID-Medium, COVID-Severe, Normal, Pneumonia, and Tuberculosis.</li>
<li><b>Methods:</b> A total of 1229 images were taken to form a dataset containing six classes corresponding to the six categories. A cGAN was used to increase the number of images. Generative Adversarial Networks (GAN) are used to train a model for generating new images. cGAN is an extension of GAN consisting of a generator and discriminator network that are trained simultaneously to optimize the model. The generated images were then trained using deep transfer learning models such as ResNet50, Xception, DenseNet169, etc. to achieve the classification into six classes.</li>
<li><b>Results:</b> The proposed model helped achieve a training and validation accuracy of up to 98.20 % and 94.21 % respectively. The model was able to achieve a test accuracy of 93.67 %. The use of cGAN not only helped to increase the size of the training dataset but it also helped to reduce the problem of over-fitting.</li>
<li><b>Conclusion:</b> The proposed approach will help to diagnose COVID-19 quickly at an early stage.</li>
</ul>
