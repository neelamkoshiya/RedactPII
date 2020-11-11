# Redact PII using Amazon Rekognition and Amazon Comprehend 
This project would help redact pii from images of driver's license and passport. In this example , for the actual machine learning and prediction, we will be using Amazon Rekognition to extract text from the images and Amazon Comprehend  to help us to identify and detect the PII. All of our image files will be read from and written to a bucket in Amazon Simple Storage Service (Amazon S3), an object storage service that offers industry-leading scalability, data availability, security, and performance. Even though this demo uses a jupyter notebook, you can write this python code in lambda and trigger this lambda when an object is uploaded in S3. This can help with automation. This example is plainly for demo and understanding.


![Architecture Diagram](https://github.com/neelamkoshiya/RedactPII/blob/main/Code/piiredaction.jpg)


[Architecture Diagram](Code/piiredaction.jpg "Architecture Diagram")

In this example, I would be using Jupyter Notebook for the demo purpose. 

Here is the notebook for driver license [Driver license pii redaction](Code/image_pii_detection-driverlicense.ipynb "Driver license pii redaction")

Here is the notebook for passport [Passport pii redaction](Code/image_pii_detection-passport.ipynb "Passport pii redaction")

