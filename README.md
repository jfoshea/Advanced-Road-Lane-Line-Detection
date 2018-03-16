# Advanced Lane Lines 

## Overview
A self driving car needs to be able to navigate a road using computer vision.  In this project we develop a more advanced lane line detection system. The project first discusses camera calibration and how to correct image distortion on the edges of images Next the perspective transform is disccused to get a birds eye view of each image this will provide more accurate lane detection. Gradient edge detection and different color spaces are then explored to determine which color spaces/channels are best for detecting lane colors accounting for differnt lighting and shadows. After we detected lane edges from the birds eye view we then search for lines from pixel intensities on the image and then apply curve fitting techniques to draw lines. Finally we implemeent a video pipeline that reads each image processs the image for lane finding and apply the extrapolated lines and predictions back on the original (unwarped) image.Many aspects of OpenCV, python, numpy, and matplotlib are used to develop the lane finder. The jupyter notebook can be found here  [AdvancedLaneLines.ipynb](https://github.com/jfoshea/SDC-AdvancedLaneLines/blob/master/AdvancedLaneLines.ipynb)

## Installing and Running the Pipeline
The following steps are used to run the pipeline:
1. Install jupyter notebook environment and packages
    ```
    https://github.com/udacity/CarND-Term1-Starter-Kit/blob/master/doc/configure_via_anaconda.md
    ```
2. Clone the SDC-AdvancedLaneLines git repository
    ```  
    $  git clone https://github.com/jfoshea/SDC-AdvancedLaneLines.git
    ```

3. enable cardnd-term1 virtualenv
    ```
    $ source activate carnd-term1
    ```
4. Run the Pipeline 
    ```
    $ jupyter notebook AdvancedLaneLines.ipynb
    ```

The output videos are:
[project_video_out.mp4] (https://github.com/jfoshea/SDC-AdvancedLaneLines/blob/master/project_video_output.mp4)
[challenge_video_out.mp4] (https://github.com/jfoshea/SDC-AdvancedLaneLines/blob/master/challenge_video_output.mp4)

## Writeup 
A detailed writeup are located here [writeup] (https://github.com/jfoshea/SDC-AdvancedLaneLines/blob/master/writeup.md)

