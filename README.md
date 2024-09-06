# Digital Image Processing - HW2
Exercises for Digital Image Processing Course - Spring 2022

By Peyman Hashemi

## Question 1: Image Point Processing
We explore various image point processing techniques. These include image negation, bit-plane slicing, histogram computation, and equalization. The exercise also involves applying thresholding and scaling operations. Finally, the task ends with histogram specification for intensity transformation.
Results: The answer is provided in following PDF


#ImageNegative #HistogramEqualization #BitPlaneSlicing
## Question 2: Motion Detection Using Bit-plane Slicing
We slice grayscale images into bit-planes and compare consecutive frames using the XOR function to detect motion. The motion is highlighted by reconstructing the image from the significant bit-planes.
Results:
<img src="https://github.com/user-attachments/assets/09c1409a-5777-40fd-b5cf-12b3779d5a8c" width=20% height=20%>
<img src="https://github.com/user-attachments/assets/193f2b0e-f919-4d16-b46f-466f0c7eba34" width=20% height=20%>
<img src="https://github.com/user-attachments/assets/ab8a44e2-9883-4fce-8ee3-d7fe3fe6e04f" width=20% height=20%>

#MotionDetection #BitPlaneXOR #FootballPlayerTracking
# Question 3: Pedestrian Detection
We apply image averaging and thresholding to detect pedestrians in video frames. The background is estimated using multiple frames and subtracted from the foreground to count individuals in test frames.
Results:
![image](https://github.com/user-attachments/assets/808e47db-bf23-4592-a0c4-bde7ce675627) ![image](https://github.com/user-attachments/assets/961ea9de-d1f5-4daa-a20e-5a5e4ffe4715) ![image](https://github.com/user-attachments/assets/d1e9987f-8868-4fd5-9411-1d830bb88af6)
#PedestrianDetection #ImageAveraging #ForegroundExtraction
## Question 4: Image Obamafication
Inspired by the iconic "Hope" poster, this exercise applies bilateral filtering and color mapping based on intensity thresholds to create a stylized effect.
Results: 
![image](https://github.com/user-attachments/assets/bde9695f-63ed-48ee-a760-66e7d8ebd2dd)

#BilateralFiltering #ColorMapping #Posterization
## Question 5: Seam Carving for Image Resizing
We use seam carving to resize images without distorting important content. The technique involves finding and removing low-energy pixel paths, reducing image dimensions while preserving key features.
Results:
https://github.com/user-attachments/assets/1a928395-5f75-4e3a-b2c3-0f769c010363

#SeamCarving #ImageResizing #DynamicProgramming
## Question 6: Explanatory Questions
A set of theoretical questions regarding spatial filters, noise reduction, and template matching were explored.
Results: The answer is provided in following PDF

#ImageFiltering #NoiseReduction #TemplateMatching
