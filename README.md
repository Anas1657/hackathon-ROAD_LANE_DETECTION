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
# Update: Added new section
# Road Lane Detection Using OpenCV
## Problem Statement
Autonomous vehicles face challenges in identifying lane markings under varying lighting and road conditions. Failure to detect lanes accurately can lead to accidents and reduced driving efficiency.
## Solution Overview
This project uses Python and OpenCV to implement a robust lane detection system. The key steps involved are:
- **Preprocessing** – Convert frames to grayscale and apply Gaussian blur.
- **Edge Detection** – Use Canny Edge Detection to detect lane boundaries.
- **Region of Interest (ROI)** – Mask the area of interest to focus on the road.
- **Hough Transform** – Detect straight lines representing lane markers.
- **Lane Overlay** – Draw the detected lanes on the original frame.
## Setup & Installation
1. **Clone the repository**:
```bash
git clone https://github.com/Anas1657/hackathon-ROAD_LANE_DETECTION.git
## Usage Instructions
- Ensure the input video file is available in the project folder.
- Run the script using:
```bash
python lane2.py

---

## **Step 6: Create `.gitignore`**
Create a `.gitignore` file to prevent unnecessary files from being uploaded:

**Example:**

---

## **Step 8: Upload and Commit**
1. Add all files to the repository:
```bash
git add .


## Demo Link
[Watch the Demo](https://your-demo-link.com)


