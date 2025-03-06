# PredatorSense
The PredatorSense Wildlife Detection System is an innovative solution designed to monitor and protect wildlife by leveraging machine learning and deep learning technologies. The system utilizes SSD MobileNet as the backbone for object detection. 

### Detection
![Detect1](https://github.com/user-attachments/assets/dffa10e3-f884-4fdc-a4b2-c1abfe46f2f1)
![Detect2](https://github.com/user-attachments/assets/28ebe4c2-a3fc-4c26-9405-a578d9904ea3)

### System Performance

<table>
  <tr>
    <td style="width: 50%; padding-right: 30px;"><h3>Min Average Precision Comparison</h3><img src="https://github.com/user-attachments/assets/4b087f34-050a-4449-8b71-386f47ec32d3" alt="mAP"></td>
    <td style="width: 50%; padding-left: 30px;"><h3>Total Loss Graph</h3><img src="https://github.com/user-attachments/assets/5f7f0dac-9ddf-4a66-811e-94735eaecce0" alt="Loss"></td>
  </tr>
</table>

The AlexNet, VGG-16, and ResNet-50 models achieved a mAP of 84.7% when evaluated on the Snapshot Serengeti and NACTI datasets in [1]. In another study [2], a self-collected dataset using a CCN model resulted in a slightly lower mAP of 77%. In contrast, our proposed system leverages SSD Mobilenet with OpenCV on the Google Open Images dataset and achieved a competitive mAP of 85.53%.

The total loss graph represents the performance of a model over time, with the loss decreasing as the number of iterations increases.

### User Interface and System Architecture

<table>
  <tr>
    <td style="width: 50%; margin-right: 15px;"><h3>User Interface</h3><img src="https://github.com/user-attachments/assets/1ac32b4d-0736-4b42-806c-92c0d359252c" alt="UIUX"></td>
    <td style="width: 50%; margin-left: 15px;"><h3>System Architecture</h3><img src="https://github.com/user-attachments/assets/53475541-f76c-47d7-b60f-440604983d19" alt="ARCH"></td>
  </tr>
</table>

### Alert System
![1](https://github.com/user-attachments/assets/46438e85-4557-41d3-94dd-4d8ab7218640)

Twilio API is integrated into the system to send SMS notifications. When wildlife is detected by the detection system, an automated process is triggered. This process utilizes Twilio's API to send a message to a designated phone number, notifying the user of the wildlife detection.

### Research Paper
You can access the detailed research paper on the system [here](https://ieeexplore.ieee.org/document/10774639).
