# Lane Detection 
## Image Prepossessing
The following operations were performed before lane de-
tection:
1) Image undistortion using cv2.undistort.
2) Image blurring using a Gaussian kernel of size 5 ×5.
3) Thresholding the gray image to get a binary image.
4) Obtained ROI, which is almost 55% of the image.


## Parameters

1) BasePath - project folder 
2) ImageFilePath - absolute path of the image files
3) CamConfigFile - path where the .yml file is
4) SaveFileName - file name for the saved video. Note: this path is relative to the BasePath

## Results
### Computing results with geometric Computer Vision
    <img src="images/lane_detect_thumbnail.jpeg?raw=true"/>

### Turn Prediction along with detection
![alt](https://github.com/Noor1886/Lane-detect/blob/master/Results/lane_detection/lane_result_2.gif)


For more details see [GitHub Flavored Markdown](https://guides.github.com/features/mastering-markdown/).
