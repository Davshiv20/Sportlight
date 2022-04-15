# Sportlight
Overview
•	Build our own highlights package in Python using a simple approach
•	Learn how automatic highlight generation works without using machine learning or deep learning!
•	We will implement our own approach to automatic highlight generation using a full-length match

Highlight Generation is the process of extracting the most interesting clips from a sports video.
You can think of this as a classic use case of video summarization. In video summarization, the full-length video is converted into a shorter format such that the most important content is preserved.
Extracting highlights manually from a full match video requires a lot of human effort. It is a time-consuming task and unless you work for a video company that does this job day in and day out, you need to find a different approach.

Here is the step-by-step process:

Input the full match video
Extract the audio 
Break the audio into chunks
Compute short-time energy of every chunk
Classify every chunk as excitement or not (based on a threshold value)
Merge all the excitement-clips to form the video highlights
 
