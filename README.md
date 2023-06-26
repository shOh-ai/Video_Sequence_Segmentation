# Video Clip Generation by Video Sequence Segmentation
<Br>

Step-1) <Br>
After divide the video into image frames. Use deep learning models that perform object detection, place recognition, and behavioral classification detect and store these elements in word form per frame.

Step-2) <Br>
Compare weighted-cosine similarity scores between stored word sets by frame to determine frame similarity to separate image sequences and generate video clips
<Br>
*Model
Object Detection with InternImage-XL <Br>
Place Recognition with Places365-CNNs <Br>
Action Classification with InternVideo-T <Br>
