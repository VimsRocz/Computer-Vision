# Overview
Background subtraction is a crucial technique in image sequence analysis, particularly in scenarios like video surveillance for pedestrian detection and tracking. This algorithm aims to distinguish between the background and foreground of an image sequence, enabling effective object detection and tracking.
## Programming Task
- Sequential Estimation of Parameters: Implementing the estimation of parameters for a single Gaussian distribution, namely the mean and variance.
- Background/Foreground Labeling: Implementing the labeling process to determine whether each pixel belongs to the background or foreground based on the variance of the background model (using a threshold at 2.5σ).
- Noise Reduction: Implementing a basic noise reduction technique using morphological operations.
- Evaluation with Different Learning Rates: Evaluate the algorithm using two different values for the learning rate: α = 1/50 and α = 1/1400.

## Written Report Questions
**1. Application of Background Subtraction Algorithm:** 
Apply the implemented algorithm to the provided image sequence. Describe the results obtained, including observations on how results vary with different learning rates and which parts of the image experience more frequent mislabeling.

**2. Meaningful Image Frames Analysis:**
   - Display the following for two selected image frames:
     - Background mean image
     - Background variance image
     - Difference image between the mean background and the current frame
     - Binary foreground/background mask
   - Indicate the frame numbers in the captions of the figures.

**3. Advantages and Drawbacks of Single Gaussian Model:** 
Discuss the advantages and drawbacks of using the single Gaussian model for background subtraction.

**4. Handling Difficult Cases:**
   - Discuss the results of the implemented method when dealing with challenging scenarios such as shadows, reflections, and stationary objects.
   - Interpret cases where pixels are wrongly labeled.

## 5. Conclusion:** 
Provide a concise summary of the findings and insights gained from implementing and evaluating the background subtraction algorithm with a single Gaussian model. Offer potential avenues for improvement and future research in the field.
