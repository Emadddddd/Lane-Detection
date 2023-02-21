# Lane-Detection
IIOT Lab Task 1
In this report, I will be going over how to make a pipeline that finds lane lines on the road by applying OpenCV functions to detect lanes in an image and later a video by following a pipeline. The following steps will be done in order to obtain the result : Greyscale imaging, Noise filtering, Smoothing, Region masking, Canny edge, Hough transformation, Video processing frame-by-frame and Saving the video as a mp4.

<ins>**Input Image:-**</ins>

![solidWhiteRight_Moment](https://user-images.githubusercontent.com/125823799/220254252-d3617d06-48ab-4e94-86d1-db198b21fccb.jpg)
![solidYellowLeft_Moment](https://user-images.githubusercontent.com/125823799/220254258-01de0665-1a0d-4ec2-b771-e301f3c1f821.jpg)

# Conclusion
In the end, the project was a success as all lanes were correctly marked on the video. 

Only straight lane lines can be identified, which is a disadvantage of this technique. The method might be altered such that it finds curved lines by utilizing poly fitting. As the lines closest to the automobile in the given video are straight, there is no issue.
