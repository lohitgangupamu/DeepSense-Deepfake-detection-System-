#Minor-2: Deepsense: An Insightful Deepfake Detection System



# Abstract


Our pioneering system is a beacon of excellence in the realm of deepfake
detection, boasting unmatched depth and sophistication in discerning manipulated
media content. With a keen understanding and perceptive eye, it excels in
identifying even the subtlest traces of falsification, setting a new standard in
detection accuracy.However, our system doesn’t stop at detection; it offers a
holistic approach encompassing thorough analysis and meaningful interpretation of
detected instances.By delving into the intricacies of synthetic media manipulation, it
provides invaluable insights into underlying techniques and motives, enabling users
to understand the evolving landscape of digital deception.More than a detection
tool, our system is dedicated to mitigating the pervasive threat posed by synthetic
media manipulation. By empowering users with knowledge and tools to navigate
this complex terrain, it serves as a bulwark against the erosion of trust and integrity
in digital content.From meticulous identification to nuanced analysis, our system
leaves no stone unturned in safeguarding the authenticity of media content. With
its comprehensive approach, it ensures a robust defense against the proliferation of
falsified content, heralding a new era of trust and transparency in the digital age.


# Aim and Project Domain


The aim of the “DeepSense: Insightful Deepfake Detection System” project is to
develop a sophisticated deep learning model integrated with Collab for real-time,
user-friendly detection, analysis, and continuous improvement of deepfake detection
capabilities, alongside educational initiatives for awareness and prevention.



The project domain of “DeepSense: Insightful Deepfake Detection System”
resides at the intersection of artificial intelligence, machine learning, cybersecurity,
and digital media integrity. Deepfakes, which are synthetic media created using
deep learning techniques to manipulate or replace existing content, have become a
pressing concern in today’s digital landscape. As such, the project aims to leverage
advanced deep learning algorithms to accurately identify and analyze deepfake
images and videos. By delving into the nuances of synthetic media manipulation,
the project seeks to provide a comprehensive understanding of deepfake techniques
and their implications for digital authenticity.
Moreover, the project extends beyond mere detection by integrating the developed
deep learning model with the Collab platform, facilitating efficient processing
and scalability. Through real-time deployment accessible via a user-friendly
web interface, the system enables individuals and organizations to effortlessly
upload and analyze media content for deepfake manipulation. Additionally, the
incorporation of Python libraries for visualization and analysis enhances users
ability to comprehend and interpret detected instances. Continuous evaluation
and improvement of the detection model ensure adaptability to emerging deepfake
techniques, while educational efforts promote awareness and best practices for
detection and prevention, ultimately fostering a safer and more resilient digital
ecosystem.


# Algorithm

1. Gather data from FF, DFDC, and Celeb-DF datasets. Combine them to create a
new dataset for real-time deepfake detection.
2. Import all videos using ‘glob‘ and read them with ‘cv2.VideoCapture‘. Extract
the first 150 frames from each video.
3. Utilize pre-trained ResNeXt50 model with 50 layers and 32 x 4 dimensions.
4. Implement LSTM for sequence processing, fitting 2048-dimensional feature
vectors as input.
5. Split dataset into 70:30 train-test ratio. Train model for 20 epochs with a learning
rate of 1e-5 and weight decay of 1e-3, using Adam optimizer.
6. Load trained model. Preprocess new video and pass to model for prediction.
Model predicts if video is real or fake with confidence.


# Steps to Implement the project


Importing Relevant Libraries
• Library Importation: Import necessary libraries such as pytorch, torchvision,face-recognition,cv2 and other required for data manipulation and model
building.
• Verify Library Versions: Check and ensure that the library versions are
compatible with the project requirements.
4.5.2 Data Collection and Preprocess The Data
• Load the Dataset: Read and load the dataset into a suitable data structure.
• Split the Dataset: Divide the dataset into training and testing sets of 70:30.
• Performance Optimization: Optimize the training and testing data for better
model performance. This may include handling missing values, scaling features,
or encoding labels.
• Data Augmentation: Apply data augmentation techniques to artificially
increase the size of the training dataset.
4.5.3 Outlining (Pre-trained ResNext50,LSTM Classifier)
• Load Pre-trained ResNext50 Model: Load the pre-trained ResNext50 model
without including the feed-forward neural network.
• Combine ResNext50 and LSTM Classifer: Combine the ResNext50 base
model with the LSTM to create the final model architecture.
• Algorithm Optimization: Optimize the algorithm by setting appropriate
hyperparameters and configurations.
• Model Training: Train the model on the prepared training dataset to learn the
patterns and features.
• Model Testing: Evaluate the trained model on the testing dataset to assess its
performance and generalization capabilities.



# Output

![output 2](https://github.com/lohitgangupamu/minor-2-/assets/110151699/a1fc16fd-95fa-469a-91dd-a2433051a60b)


# Contributors

1. G.LOHIT
2. K.S.L.N REDDY
3. G.SRINIVAS



