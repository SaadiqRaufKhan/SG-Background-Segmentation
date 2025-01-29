# Adaptive Background Segmentation using Gaussian Mixture Models  

This project implements an adaptive background subtraction algorithm based on **Stauffer and Grimson's method**, utilizing Gaussian Mixture Models (GMMs) for robust video frame segmentation into foreground and background.  

## Features  
- **Dynamic Background Modeling:** Handles complex scenes with lighting changes, repetitive motions, and long-term scene variations.  
- **Foreground Segmentation:** Effectively detects and isolates moving objects in video sequences.  
- **Real-time Performance:** Designed for efficiency and adaptability.  

## Technologies  
- **Programming Language:** Python  
- **Libraries:** OpenCV, NumPy, Matplotlib  
- **Environment:** Jupyter Notebook  

## How It Works  
1. **Background Modeling:**  
   Each pixel is modeled as a mixture of Gaussians to account for variations in lighting and repetitive background patterns.  
2. **Foreground Detection:**  
   Pixel values that do not match the background model are classified as part of the foreground.  
3. **Adaptive Learning:**  
   The model dynamically updates based on new frame data to maintain robustness over time.

## Videos

- **Original Video:** [Link to Original Video](https://drive.google.com/file/d/1li4pvfcCzcc1B5HhWr6FeedATnYy7V6v/view?usp=sharing)
- **Foreground Segmentation:** [Link to Foreground Video](https://drive.google.com/file/d/1czujopOJfvR2byIC37UBrUXVHLLbgYes/view?usp=sharing)
- **Background Model:** [Link to Background Video](https://drive.google.com/file/d/1Q0AQ2syGgpdeJzkQd9ksMJGgq_xYOPgT/view?usp=sharing)

## Results

The system successfully segments video frames into:
 - **Foreground objects:** Detecting and tracking moving objects in the scene.
 - **Background models:** Dynamically learning and adapting to the static parts of the scene.

## References
  - Stauffer, C., & Grimson, W. E. L. (1999). Adaptive Background Mixture Models for Real-Time Tracking.
