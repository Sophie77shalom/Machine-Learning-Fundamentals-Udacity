## Landmark Classification & Tagging for Social Media

In this project, I applied the skills acquired in the Convolutional Neural Network (CNN) course to build a landmark classifier, aimed at enhancing photo sharing and storage services. These services often benefit from having location data for each photo uploaded, as it allows for advanced features like automatic tagging and photo organization, thus providing a compelling user experience.

However, many photos lack location metadata due to various reasons, such as the absence of GPS in the capturing device or privacy concerns that lead to metadata scrubbing. To address this, the project aims to infer the location of an image by detecting and classifying discernible landmarks within it. Given the vast number of landmarks worldwide and the immense volume of photos uploaded daily, manual classification is impractical, necessitating an automated approach.

Project Steps
Data Preprocessing:

Collected and prepared a diverse dataset of images featuring various landmarks.
Performed data augmentation and normalization to enhance model robustness and performance.
Designing and Training CNNs:

Built and trained multiple CNN architectures from scratch to classify landmarks in the images.
Applied transfer learning techniques using pre-trained models to improve accuracy and reduce training time.
Model Evaluation:

Compared the performance of different CNN models based on accuracy and other relevant metrics.
Fine-tuned hyperparameters and selected the best-performing model for deployment.
Deployment:

Developed an app to demonstrate the practical application of the trained CNN.
Integrated the model into the app to automatically predict the location of uploaded images based on identified landmarks.
