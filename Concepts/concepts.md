# YOLO - You Only Looks Once
<pre>
YOLO is a real time object detection algorithm, which is known for its accuracy with minimal background errors it process images at an impressive 45 frames per second
</pre>

<b> R-CNN - Region based Convolution Neural Network (R-CNN) </b>

## What is a Convolutional Neural Network (CNN)?

A Convolutional Neural Network (CNN) is a specialized type of deep learning algorithm that is particularly well-suited for image recognition and processing tasks[1][2][3][4]. It is inspired by the structure of the human visual cortex and has a hierarchical architecture that allows it to learn and extract features from images at different scales[1][2].

CNNs are made up of multiple layers, including convolutional layers, pooling layers, and fully connected layers[1][2][3]. The key components of a CNN are:

- **Convolutional Layers**: Apply convolutional operations to input images using filters (kernels) to detect features like edges, textures, and patterns[1][2][4].
- **Pooling Layers**: Downsample the spatial dimensions of the input, reducing computational complexity[1][2].
- **Activation Functions**: Introduce non-linearity, allowing the model to learn complex relationships[1].
- **Fully Connected Layers**: Make predictions based on the high-level features learned by previous layers[1][2].

## How CNNs Work

CNNs work by applying a series of convolutional layers to the input image[1][2][3][4]. Each convolutional layer applies a filter to the input, generating a feature map that represents the presence and intensity of detected features[4].

The process involves[4]:

1. Sliding a filter (kernel) over the input image
2. Calculating a dot product between the kernel weights and the pixel values under the kernel
3. Transforming the input into a set of feature maps

Deeper layers receive input from previous layers' feature maps, enabling them to detect more complex patterns[4]. Between layers, pooling operations downsample the feature maps to reduce dimensionality[1][2].

In the final layers, fully connected layers make predictions based on the learned features[1][2][4].

## Applications of CNNs

CNNs have a wide range of applications due to their effectiveness in processing visual data[3][4][5]:

- Image classification
- Object detection
- Image segmentation
- Image generation
- Video analysis
- Medical image analysis
- Self-driving cars
- Facial recognition

## Advantages of CNNs

- Ability to automatically extract relevant features from raw image data[3]
- Translation-invariant characteristics that allow identifying patterns regardless of position or orientation[3]
- Availability of pre-trained models that can be fine-tuned for new tasks with little data[3]
- Versatility in application to various domains beyond images, such as natural language processing and time series analysis[3]

 ## R-CNN
R-CNN (Region-based Convolutional Neural Network) is a pioneering deep learning object detection algorithm that combines the power of convolutional neural networks (CNNs)

 ### SUMO
  ```
  Simulation of Urban MObility
  ```
