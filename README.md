
---

# Real-Time Face Detection using YOLOv5

## 🚀 Project Overview

Welcome to **Real-Time Face Detection**! This project uses **YOLOv5**, a state-of-the-art **object detection** model, to detect faces in real time. It can be applied to webcam streams or uploaded video/media files, providing fast and accurate face detection in dynamic environments.

With the power of **YOLOv5**, this system is optimized for performance and can detect multiple faces in various orientations in real time. Whether you're building a **security system** or a **smart assistant**, this project serves as an excellent starting point.

---

## ✨ Features

- **Real-Time Detection**: Detect faces instantly via webcam or video stream.
- **Uploaded Media Support**: Analyze and detect faces from video or image files.
- **High Accuracy**: Leverages the YOLOv5 deep learning model for precise detection.
- **Easy Integration**: Simple to use with a few Python scripts and minimal setup.

---

## 🔧 Installation

### Prerequisites

Before you start, make sure you have **Python 3.7+** installed on your system. You’ll also need to install the required Python libraries.

### Steps

1. **Clone the repository**:
   ```bash
   git clone https://github.com/muhammadnouman911/Real_Time_Face_Detection.git
   cd Real_Time_Face_Detection
   ```

2. **Install dependencies**:
   ```bash
   pip install -r requirements.txt
   ```

3. **Download YOLOv5 pre-trained model**:
   - If the model file is not included in the repository, download it from [YOLOv5 official page](https://github.com/ultralytics/yolov5) or use the included `yolov5m.pt` file.

---

## ⚡ How to Use

### 1. **Real-Time Face Detection (Webcam)**

To run the **real-time detection** using your webcam, execute the following command:

```bash
python realtime_detection.py
```

This will open a window showing your webcam feed, and faces will be detected and highlighted in real time.

### 2. **Face Detection on Uploaded Media (Images or Videos)**

To analyze an uploaded media file for face detection, use the following command:

```bash
python upload_media_analysis.py
```

You’ll be prompted to select an image or video file, and the system will detect faces in the media, displaying the results.

---


## 📂 File Overview

- **app.py**: Main application file for loading the YOLOv5 model and handling video input for face detection.
- **realtime_detection.py**: Handles real-time face detection via webcam.
- **upload_media_analysis.py**: Handles face detection for uploaded image or video files.
- **yolov5m.pt**: Pre-trained YOLOv5 model for face detection.
- **requirements.txt**: List of all required Python libraries.

---

## 💡 Contribution

Contributions are welcome! If you have suggestions or improvements, feel free to create a **pull request** or open an issue. Help improve face detection in real-time environments!

1. Fork the repository
2. Create a new branch (`git checkout -b feature-branch`)
3. Make your changes and commit (`git commit -am 'Add feature'`)
4. Push to the branch (`git push origin feature-branch`)
5. Create a new **pull request**

---

## 📝 License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

---

## 📞 Contact

If you have any questions or need further assistance, feel free to reach out to me:

- **GitHub**: [@muhammadnouman911](https://github.com/muhammadnouman911)
- **Email**: [your-email@example.com](mailto:your-email@example.com)

---

### Thank you for checking out **Real-Time Face Detection**! Happy coding! 😄

---
