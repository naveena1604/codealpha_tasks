# 🛰️ Task 4 – Object Detection and Tracking

Real-time Object Detection and Tracking using YOLOv8 and Deep SORT (Task 4 - CodeAlpha AI Internship)

This project is developed as part of my **Artificial Intelligence Internship at CodeAlpha (June–July 2025)**.  
The objective of this task is to detect and track objects in a video stream using the **YOLOv8** object detection model and **Deep SORT** tracking algorithm.

---

## 📌 Project Objective

- Use a pretrained YOLOv8 model to detect objects in video frames  
- Track detected objects using Deep SORT and assign consistent IDs  
- Display real-time bounding boxes and tracking labels  
- Save the output as a processed video file  
- Provide visual demo and clean code for object tracking

---

## 🗃️ Files in This Repository
📁 Task_4_Object_Tracking/
      code_alpha_task_4.py 
      task4video.mp4 # Original input video
      Task4 Code Screenshots/ # Screenshots of code and results
      README.md # Project documentation (this file)

---

## 🧠 Core Functionality

- Load video file and process it frame-by-frame  
- Apply YOLOv8 for object detection  
- Use Deep SORT to track detected objects  
- Annotate frames with bounding boxes, class names, and tracking IDs  
- Save processed frames as a new output video file

---

## 🧪 Workflow

1. Load video using OpenCV  
2. Run detection on each frame using YOLOv8  
3. Format detection results and send to Deep SORT  
4. Annotate results with rectangles and labels  
5. Write processed frames to an output video

---

## 🖥️ Demo Video

🎥 [Click to Watch Demo](https://drive.google.com/file/d/1o8MYOUKxjuzDs0wFqwU1H6byuC-SSQtM/view?usp=sharing)

---

## Input video

🎥 [Click to Watch Input video](https://drive.google.com/file/d/1IJXE-MhTQ8wDowVhYyfMvW9fjQ2W07sN/view?usp=sharing)

---

## 🔗 LinkedIn Post

🔗 [View LinkedIn Post](https://www.linkedin.com/posts/naveena-sivaiah-91b0b6326_aiinternship-objectdetection-codealpha-activity-7343246283270230017-QGle?utm_source=social_share_send&utm_medium=android_app&rcm=ACoAAFI9iKcBwcCFvahb-MaFocwHJSF22yC6mYE&utm_campaign=copy_link)

---

## 🧰 Technologies Used

- Python  
- YOLOv8 (`ultralytics`)  
- OpenCV  
- Deep SORT (`deep_sort_realtime`)  
- Google Colab (for initial development)  
- Video I/O and visualization

---

## 🚀 How to Run

1. ✅ Install required libraries:
   pip install ultralytics opencv-python deep_sort_realtime

2. ✅ Place your input video in the same directory, named:
    input_video.mp4

3. ✅ Run the script:
    python code_alpha_task_4.py


---

## 📌 Tags

#CodeAlpha #AIInternship #ObjectDetection #ObjectTracking #YOLOv8 #DeepSORT #ComputerVision #Python #OpenCV #DeepLearning #VideoAnalytics #InternshipProject

    
