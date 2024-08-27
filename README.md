# Optical-Character-Recognition
Extracting the text as output by passing a video as an input using CV, Torch, Python supported libraries
 # IN MODULE
      This Python script processes a video file using EasyOCR for text recognition, and it is optimized to run on a GPU if available.
 # Libraries:
 
# 1. OpenCV (cv2):
 Provides functionalities for reading, resizing, and writing video files, as well as performing image processing tasks.
cv2.VideoCapture: Opens video files for reading.
cv2.resize: Resizes images.
cv2.VideoWriter: Writes processed frames to an output video file.

# 2.EasyOCR (easyocr.Reader):
                   Performs Optical Character Recognition (OCR) to extract text from images.
                   reader.readtext: Extracts text from an image.
# 3.Time (time):
              Measures execution time to calculate FPS and processing duration.
time.time(): Records current time to measure elapsed time.

# 4.Frame Skipping (frame_skip):
           The interval at which frames are processed from the video. For example, processing every 100th frame instead of every frame.
# 5.Image Resizing (resize_factor):
       The factor by which frame dimensions are reduced to speed up processing. For instance, a resize_factor of 0.5 halves the dimensions of each frame.
# 6.OCR (reader.readtext):
        Optical Character Recognition, a technology for extracting text from images. In the code, reader.readtext is used to perform OCR on the frames.
# 7.FPS (Frames Per Second):
         A measure of how many frames are processed per second. Higher FPS indicates smoother and faster processing.
# 8.Codec (cv2.VideoWriter_fourcc):
      A software component that compresses and decompresses video files. XVID is one example used for writing output videos.
# 9.Bounding Boxes:
     Rectangles drawn around detected text regions in frames to highlight the text. Used in conjunction with cv2.rectangle to visualize OCR results.
# OUTPUT
 It is saved in Audio-Video Interleave(.avi) format 

