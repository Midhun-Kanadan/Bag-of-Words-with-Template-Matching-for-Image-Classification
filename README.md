
# Project Title

## Overview
This project focuses on the implementation of Template Matching and Bag of Visual Words techniques in image processing. The main objective is to apply these techniques for pattern recognition in a set of images.

## Task 1: Template Matching

### Objective
- Implement a custom function for template matching.
- Compare results with built-in functions.
- Investigate the effect of different scales.

### Steps
1. **Download Images and Visual Words**
   - Get the images from `images.zip`.
   - Download visual words from `words.zip`.

2. **Implement Template Matching**
   - Develop a custom function for template matching.
   - Use Normalized Cross-Correlation (NCC) to compute similarity.

3. **Result Analysis**
   - Identify the best fit location using the highest NCC value.
   - Analyze how different scales affect the results.

4. **Visualization**
   - Plot four examples where the template is successfully found.
   - Highlight the template position with a bounding box.

## Task 2: Bag of Visual Words

### Objective
- Use template matching to compute association strength between visual words and images.
- Implement k-nearest neighbors (kNN) for image classification.

### Steps
1. **Feature Vector Computation**
   - Develop a function to return a feature vector for an image.
   - Each vector has 6 values representing the highest NCC for each visual word.

2. **Feature Vector Analysis**
   - Compute feature vectors for all 6 images.
   - Plot these vectors: x-axis for visual word index, y-axis for NCC value.

3. **kNN Implementation and Classification**
   - Implement the kNN algorithm with k=3.
   - Classify test images based on majority voting procedure.

4. **Classification of Test Images**
   - Use images 1 to 4 as training samples.
   - Run kNN on test images 5 and 6.
   - Plot the results with the predicted class.

## Requirements
List any libraries or dependencies required for this project.

## Installation
Provide instructions on how to set up the project.

## Usage
Describe how to run the tasks and any relevant scripts.

## Contributing
Guidelines for contributing to this project.

## License
Specify the license under which this project is released.
