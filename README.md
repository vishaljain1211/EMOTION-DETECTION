Here the above files contain a fully developed module and using that I have implemented to detect emotions from a video.


--Detect facial expression from video file


run "python videoFrameRead.py --video-file [your video file.mov]" where the video file needs to be in current directory

Additional tags:


--frame-step the frame rate at which predictions are made, default was set to 10 frames


--save to save video with predictions and landmarking


--savedata to save csv file with expression predictions, their probability tensor and eye aspect ratio
