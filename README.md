1. Make
a. Open a terminal in the build folder and type cmake .. and Enter
b. type make and Enter

2. In build folder Exe can be started using following command

./OPENCVAnnotation -images=/home/shoaib/Mywork/RoboSystems/Robocart/Caffe_Classifier/images -annotations=/home/shoaib/Mywork/RoboSystems/Robocart/Caffe_Classifier/images/annotation.txt
Two parameters should be used
1. input images folder (to be at ease plz place each product in seperate folder and run proces for each product)
2. path to output file name

Drag mouse on the product to draw a rectangle

You can use following command on it

ASCII KEYS
        //      c = 99       add rectangle to current image
        //      n = 110      save added rectangles and show next image
        //      d = 100      toggle difficulty level
        //      r = 114      delete the last annotation made
        //      u = 117      upper label
        //      l = 108      lower label
        //      + = 43       increment image no for file writing
        //        <ESC> = 27      exit program# devops
