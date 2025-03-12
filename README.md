# hackathon-ROAD_LANE_DETECTION
The Road Lane Detection System aims at improving autonomous car safety by identifying road lane markings with high precision. The system applies computer vision methods to identify lanes and display real-time visual feedback to avoid lane crossing and enhance driving accuracy.
# Road Lane Detection Using OpenCV  

## 🏆 Problem Statement  
Autonomous vehicles face challenges in identifying lane markings under varying lighting and road conditions. Failure to detect lanes accurately can lead to accidents and reduced driving efficiency. This project aims to create a robust lane detection system to enhance vehicle safety and driving accuracy.  

---

## 🚀 Solution Overview  
This project uses **Python** and **OpenCV** to implement a lane detection system that accurately identifies lane boundaries in real-time video streams. The key steps involved are:  

1. **Preprocessing**  
   - Convert frames to grayscale.  
   - Apply Gaussian blur to reduce noise.  

2. **Edge Detection**  
   - Use Canny Edge Detection to identify lane boundaries.  

3. **Region of Interest (ROI)**  
   - Mask the area of interest to focus on the road.  

4. **Hough Transform**  
   - Detect straight lines representing lane markers.  

5. **Lane Overlay**  
   - Draw the detected lanes on the original frame for visual output.  

---

## 🛠️ Setup & Installation  
Follow these steps to set up and run the project:  

### 1. **Clone the Repository**  
```bash
git clone https://github.com/Anas1657/hackathon-ROAD_LANE_DETECTION.git
2. Create a virtual environment:  
3. Activate the virtual environment:  
- **Windows:**  
4. Install dependencies:  

---

## 🚀 **Usage Instructions**  
1. To train the model:  
2. To run lane detection on video:  
3. To exit, press **'q'** while the video is running.  

---

## 🌟 **Technologies Used**  
- Python  
- OpenCV  
- NumPy  

---

## 🎥 **Demo Video**  
[Click here to view the demo](#)  

---

## 🛠️ **Project Structure**  
📂 Road_Lane_Detection
├── frames/
├── lane2.py
├── lane_training.py
├── requirements.txt
├── README.md
└── .gitignore


---

## 🙌 **Contributors**  
- MOHAMMAD ANAS
## Demo Link
https://drive.google.com/file/d/1BzLHd86QK2rBDZdPFopNRLVfwDMT_F87/view?usp=drivesdk)


---

## 📄 **License**  
This project is licensed under the MIT License.  






