# Sportlight
Overview</br>
•	Build our own highlights package in Python using a simple approach<br/>
•	Learn how automatic highlight generation works without using machine learning or deep learning!<br/>
•	We will implement our own approach to automatic highlight generation using a full-length match<br/>

Highlight Generation is the process of extracting the most interesting clips from a sports video.
You can think of this as a classic use case of video summarization. In video summarization, the full-length video is converted into a shorter format such that the most important content is preserved.
Extracting highlights manually from a full match video requires a lot of human effort. It is a time-consuming task and unless you work for a video company that does this job day in and day out, you need to find a different approach.</br>

Here is the step-by-step process:

Input the full match video from the user<br/>
Extract the audio using librosa library from Python <br/>
Break the audio into small chunks<br/>
Listen to those chunks <br/>
Compute audio signal of every chunk<br/>
Classify every chunk as excitement or not (based on a minimum threshold value)<br/>
Merge all the excitement-clips to form the video highlights<br/>





  **The code implementation has started but our team feel it's not fit enough yet to be shown for judgement hence we haven't uploaded it yet**
