# Face-Detection-Model

This project implements a face detection system using OpenCV in Python. The main objectives include:

- **Real-time Face Detection:** Captures video feed from a camera and identifies faces in real time.
- **Image Saving:** Automatically saves detected faces as images for further analysis or processing.
- **Efficient Image Management:** Utilizes Python's OS and UUID libraries for systematic image storage.

## Key Features

- **OpenCV Integration:** Leverages OpenCV for face detection and image handling.
- **Real-time Processing:** Ensures quick and efficient face recognition during video capture.
- **Automated Workflow:** Automatically captures and stores face images without manual intervention.

## How to Use

1. **Setup:** Ensure you have OpenCV installed by running:
    ```bash
    pip install opencv-python
    ```

2. **Run the Script:** Execute the main script to start capturing images from your webcam.

3. **View Results:** Captured face images will be stored in the specified directory.

This project is a foundational implementation aimed at real-time face detection and can be extended for more advanced applications like facial recognition, emotion detection, or security systems.

## Note
- Run the code on an enviorement having Tensorflow(Latest version) and CV2 installed.
- Run the whole file let your webcam take photos, create the folders needed manually.
- The model will be saved as
  ''' bash
   FileName.h5
  '''
  file that can be used for further integration to any system as per usfulness. 
