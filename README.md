# Optical-Flow_JASOn-extraction
Optical Flow_JASOn extraction 

error                                     Traceback (most recent call last)
<ipython-input-13-fb4f370d869f> in <module>()
     84         prevgray = gray
     85 
---> 86         cv.imshow('flow', draw_flow(gray, flow))  #its shows the image
     87         if show_hsv:
     88             cv.imshow('flow HSV', draw_hsv(flow))

error: /home/travis/miniconda/conda-bld/conda_1485299292920/work/opencv-3.2.0/modules/highgui/src/window.cpp:304: error: (-215) size.width>0 && size.height>0 in function imshow



cv.calcOpticalFlowFarneback(prevgray, gray, None,   0.5, 3, 15, 3, 5, 1.2, 0) :
http://funvision.blogspot.com/2016/02/opencv-31-tutorial-optical-flow.html

https://docs.opencv.org/2.4/doc/tutorials/imgproc/pyramids/pyramids.html

https://docs.opencv.org/2.4/modules/imgproc/doc/filtering.html?highlight=pyrup#pyrup


ch = cv.waitKey(20)
https://codeyarns.com/2015/01/20/how-to-use-opencv-waitkey-in-python/
