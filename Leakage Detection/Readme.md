### Week 1: 06 July 2021 to 12 July 2021

Following is the summary or takeaway from some of the research papers available from the internet

#### 1. [A Convolutional Neural Network based solution for Pipeline Leak Detection (Oct'19)](https://github.com/sharvaree1921/TechMahindra/blob/main/Leakage%20Detection/AConvolutionalNeuralNetworkBasedSolutionforPipelineLeakDetection.pdf)

- A novel approach for pipeline leak detection
in which video images from **IoT cameras** installed across
various locations on the pipelines are continuously analyzed
and a convolutional neural network model is implemented for
detecting oil leaks from the pipeline is proposed.
- An implementation
of the **CNN** known as the **Single Shot Detection (SSD)**
algorithm leverages on the CNN through the use of
various activation maps for its prediction classes.
- Pipeline leak detection methods could be classified based
on intervention means as manual, automated or semi-
automated detection or based on inference as either direct or
indirect inference.
  - **__Manual detection__** is conducted by hu-
mans
  - **__Semi-automated involves__** solutions that are mostly car-
ried out only with complementary input from humans
  - **__Automated detection__** is achieved entirely without humans
in the decision making process
- Pipeline leak detection could also be classified as hardware
based or software based.
  - Hardware: Acoustic Detection, Optical Methods, ultrasonic flowmeters
  - Software: real-time
transient modelling, mass/volume balance measurement and negative pressure wave measurement
- IoT devices usually generate massive amounts of data
which are then transmitted to the cloud for processing. For
pipeline leak detection, such data could include temperature,
flow, vibration or image data. In this research paper, image data is used.

![image](https://github.com/sharvaree1921/TechMahindra/blob/main/Leakage%20Detection/Images/image.png)

- The proposed solution incorporates the Single Shot De-
tector (SSD) algorithm which improves on the CNN by **performing both image classification and image localization**
tasks during a single forward pass of the CNN.
- The SSD
algorithm applies a **bounding box technique** and an object
detector which classifies the detected region as indicated on
a label map
- The muti-scale sliding window
detector in SSD is able to produce finer accuracy through
the use of multiple layers. This finer accuracy is required for
detecting smaller particles of leak that will be detected.
- Proposed Solution: Less Complex, uses multiple measurement parameters, doesn't require online connectivity, solution is more practicable since the IoT
cameras can be deployed in sheltered locations such as oil
platforms and drilling rigs, solution is also more effective in terms
of response time than alternative solutions that use UAVs
since the proposed IoT cameras will be fixed and stream
continuously from the pipeline.

#### 2. [Applying Convolutional Neural Networks
to Detect Natural Gas Leaks
in Wellhead Images (Oct'20)](https://github.com/sharvaree1921/TechMahindra/blob/main/Leakage%20Detection/09226415.pdf)

- Previous studies used image processing techniques associated with a novelty filter classifier to detect presence or absence of visible cloud of hydrocarbon vapors i.e. Natural Gas plume in cctv frames. This paper introduces improved method that enhances results obtained previously along with the **Gradient-weighted Class Activation Mapping Algorithm(Grad-CAM)** to identify natural gas leaks. **CNN** are used to classify CCTV images.
- Accuracy: 99.78% and False Negative Rate: 0.00%
- Previous works of detection of combustible images used thermal images, whereas this study uses visible images(Simple CCTV frames)
- Another objective of the work is to provide a **location
map** that highlights the most important regions in the image
that contributed to the detection of natural gas leakage, that
is, this work will generate visual explanations of the leak,
which would help untrained users to discern the leak location.
For this the Gradient-weighted Class Activation
Mapping (Grad-CAM) technique is used.
- To minimize overfitting, **data augmentation** technique and **transfer learning** techniques are used. in tL, pre-trained deep networks were evaluated such as _Alex Net_, _Dense Net_, _Google Net_, _MobileNet-V2_, _ResNet-18_, _VGG-16_
- Refer the [research paper](https://github.com/sharvaree1921/TechMahindra/blob/main/Leakage%20Detection/09226415.pdf) directly to study related works of Novelty filter, past work on cloud, smoke classification, use of GANs, etc.
-  Methodolgy:
![]()