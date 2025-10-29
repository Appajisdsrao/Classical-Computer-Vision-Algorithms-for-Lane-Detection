# Classical-Computer-Vision-Algorithms-for-Lane-Detection
This project implements and demonstrates core classical computer vision algorithms
Hough Transform (lines, circles, ellipses) and Template Matching on the TuSimple road lane detection dataset. It is designed as a practical exploration of traditional CV techniques, as required for Unit 3 of most university machine learning and computer vision courses.

Features
Hough Line Detection: Identifies straight lanes and road boundaries in real driving scenes using the Hough Transform.

Hough Circle Detection: Detects circular features (such as wheels, round signs) and demonstrates behavior on road scene textures.

Ellipse Detection: Fits ellipses to contours in the images; useful for finding oval-shaped objects.

Template Matching: Locates custom objects or patterns in road images, illustrating the generalized Hough concept.

Visualized Results: Output images show overlays of detected lines, circles, ellipses, and template boxes for easy interpretation.

Dataset
TuSimple Lane Detection Dataset
Source: TuSimple Kaggle
Contains real-world highway driving frames, perfect for testing classical vision algorithms.

Usage
Setup environment

Requires Python, OpenCV, Matplotlib, and NumPy.

Download the TuSimple dataset from Kaggle.

Run provided notebooks or scripts

All major algorithms are demonstrated step-by-step.

Visual outputs can be used directly in reports/project submissions.

Example Results
Lane detection correctly identifies most yellow/white markings.

Circle and ellipse detection shows how background textures impact classical feature detection.

Template matching robustly finds small distinctive road markers.

How It Works
Hough Transform algorithms work by converting edge maps to a parameter space, accumulating votes for possible geometric shapes.

Template Matching uses cross-correlation to find locations of a given template within the full image.

Code Structure
lane_detection_demo.ipynb — main notebook with all classical CV methods.

images/ — folder containing sample outputs and template crops.

Scripts are modular, easy to adapt to new datasets.

License
This project is for academic and educational use only.

Author
APPAJI SREE DHARMA SHASTA RAO, RA2211026010162, 7TH SEM.

