# **Real-life Object Detection**

## **Overview**

This project leverages the YOLOv5 (You Only Look Once) model to perform real-time object detection on images and videos. By using a dataset of approximately 13,000 images, the system is capable of identifying and classifying 19 real-world objects, such as cars, buses, chairs, and people, with high accuracy and efficiency.

---

## **Features**

- **Object Detection**:
  - Detects and classifies objects in real-time.
  - Highlights detected objects with rectangular bounding boxes.

- **Versatile Input Support**:
  - Processes static images and video files.
  - Real-time detection using laptop and mobile cameras.

- **Comprehensive Training**:
  - Model trained on a robust dataset of nearly 13,000 images.
  - Covers a diverse set of 19 object classes, ensuring reliability across various scenarios.

- **Optimized Performance**:
  - Utilizes YOLOv5 for its speed and accuracy, making it suitable for real-time applications.

---

## **Technologies Used**

- **Model**: YOLOv5 (PyTorch-based implementation)
- **Programming Language**: Python
- **Libraries**:
  - OpenCV: For video processing and camera integration.
  - PyTorch: For model implementation and inference.
  - NumPy, Matplotlib: For data manipulation and visualization.

---

## **Object Classes**

The system can detect the following objects:
- Cars, Buses, Motorcycles
- People, Chairs, Tables
- Traffic Lights, Stop Signs, Backpacks
- And more...

---

## **How It Works**

1. **Input Processing**:
   - Accepts images, video files, or real-time input from cameras.
   
2. **Object Detection**:
   - YOLOv5 detects objects and marks them with bounding boxes.
   - Classifies each detected object into one of the 19 predefined categories.

3. **Output**:
   - Annotated images or video streams with detected objects and their labels.

---

## **How to Use**

1. Clone the repository:
   ```bash
   git clone <repository_url>
   ```
2. Install dependencies:
   ```bash
   pip install torch torchvision opencv-python numpy matplotlib
   ```
3. Run the detection script:
   ```bash
   python detect_objects.py --source <input_source>
   ```
   - Replace `<input_source>` with the path to an image, video, or a camera index (e.g., `0` for laptop camera).

---

## **Future Enhancements**

- Expand object classes to include more categories.
- Integrate a web-based or mobile-friendly interface for easier use.
- Enhance performance for edge devices like Raspberry Pi.

---

## **License**

This project is licensed under the [MIT License](https://opensource.org/licenses/MIT).

