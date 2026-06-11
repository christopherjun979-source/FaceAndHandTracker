# Hand Tracker

A real-time 3D hand tracking website built with HTML, CSS, and JS using MediaPipe to study Parkinson's disease movements. The system tracks 21 points per hand with color-coded fingers. It uses persistent data panels, while featuring a live FPS counter with no extra hardware needed.

## Live Demo
Try the dashboard directly in your browser:
**https://christopherjun979-source.github.io/ParkinsonHandTrack/**

## Features

* **Anatomical Tracking:** Measures X, Y, and Z spatial coordinates for 21 separate joint landmarks on each hand.
* **Color-Coded Mesh Tracking:** Maps distinct visual identifiers to the real-time camera overlay, matching coordinate data seamlessly with the hand mesh:
  * **Wrist Base:** Highlighted in red
  * **Thumb:** Highlighted in orange
  * **Index Finger:** Highlighted in yellow
  * **Middle Finger:** Highlighted in green
  * **Ring Finger:** Highlighted in blue
  * **Pinky Finger:** Highlighted in purple
* **Granular Landmark Isolation:** Separates and displays tracking telemetry for all 21 individual joint coordinates simultaneously, allowing for easy side-by-side data comparison.
* **Performance Diagnostic Overlay:** Features an integrated, live frames-per-second (FPS) counter to monitor video processing efficiency and stream stability.

##  How to Use

1. Open the live demo link in any standard web browser.
2. Grant camera permissions when prompted by the application.
3. Place one or both hands into the frame to view the live tracking data.

---
*Note: This project is a work-in-progress, may not be 100% accurate at all times, and will be continuously updated in the future.*
