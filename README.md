# Lucas-Kanade

# Optical Flow Detection using Lucas-Kanade Method

This project implements the **Lucas-Kanade** method to detect and track optical flow in a video using Python and OpenCV. Optical flow refers to the pattern of apparent motion of objects, surfaces, and edges in a visual scene caused by the relative motion between an observer and the scene.

---

## 🔍 What is Lucas-Kanade Optical Flow?

The **Lucas-Kanade** method is a differential technique for optical flow estimation. It assumes that the flow is essentially constant in a local neighborhood of the pixel under consideration. It works well for small and consistent motion between frames.

---
## 🛠️ Technologies Used

- Python 3.x
- OpenCV (cv2)
- NumPy

---
---

## 🔄 Method Overview

1. Read input video frame-by-frame.
2. Convert frames to grayscale.
3. Detect good features to track using `cv2.goodFeaturesToTrack()`.
4. Use `cv2.calcOpticalFlowPyrLK()` to compute motion vectors.
5. Draw optical flow tracks to visualize movement.

---

## 🎯 Features

- Corner detection using Shi-Tomasi method
- Optical flow tracking with pyramidal Lucas-Kanade
- Overlay of motion vectors on video frames
- Output visualized and optionally saved

---
---

## 📷 Sample Output

The project outputs a video showing motion vectors for selected keypoints across frames, highlighting how features move through time in the video.

---

## ✅ Conclusion

This project is a practical implementation of the Lucas-Kanade algorithm for optical flow, useful in motion tracking, video analysis, and robotics applications. It provides a foundational understanding of temporal motion estimation in computer vision.

---
