# Rice-Leaf-Disease
![rice](https://user-images.githubusercontent.com/95012573/147822839-fcf88bbd-8469-4bb8-9251-5ac7ce713714.png)


Rice is one of the most popular staple food crops grown mainly across Asia, Africa and South America but is susceptible to a variety of pests and diseases.Physical characteristics such as decolorization of leaves can be used to identify several diseases that may affect the rice crop. For example, in the case of Brown-Spot, a fungal disease that affects the protective sheath of the leaves, the leaves are covered with several small oval brown spots with gray centers whereas, in the case of Leaf-Blast, the leaves are covered with larger brown lesions. Similarly, the leaves affected by the Rice Hispa pest can be identified by the long trail marks that develop on the surface of the leaf.

This study aims to help farmers by early detection of disease through rice leaf image processing using convolutional neural networks and transfer learning . The model is trained on the Rice Disease Image Dataset  which includes over 120 rice leaf images. Over 3 categories: Leaf Blast, Brown Spot, Bacterial leaf blight; the model performs well at good accuracy. We also looked at transfer learning and the result is gbest compare to CNN. Furthermore, we saw that the model is capable even for cases where the symptoms of the disease are still very small. This model gives farmers ample time to potentially save their crops, have better yield, and save cost from fertilizers and pesticides.A Convolutional Neural Network (CNN) is trained on a dataset consisting of images of leaves of both healthy and diseased rice plants. 
# Proposed Method
We split the image dataset into training, validation and testing image sets. To prevent overfitting, we augment the training images by scaling and flipping the training images to increase the total number of training samples. In order to learn the features of the training images, we use a method called Transfer Learning wherein the ‘top’ layers of a pre-trained model are removed and replaced with layers that can learn the features that are specific to the training dataset.
# Conclusions
We described how we used transfer learning to classify images of diseased and healthy rice leaves. MobileNet-v2 had best accuracy  and is best suited for mobile applications with memory and processing constraints. For cropped images of Rice Hispa, we observed a significant increase in the classification accuracy compare to CNN.
