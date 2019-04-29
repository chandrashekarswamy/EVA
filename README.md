# convolutional-neural-network

## Assignment 1B

* Kernels 
    Kernels are feature extractor or filters, we use 3*3 matrix to extract the necessary feature from the input file.
    OR
    Kernel is a key functions used to extract necessary information from the frame/picture so that we can take certain decision to 
    identify the edges & Gradients/texture/patterns/parts of object/object.
    
* Channels
    Channels are set of similar features OR Fundamental building blocks of images.
    
* 3*3
    We need to use 3*3 because it uses less number of values get the results compared to other kernels
    example : 
          5*5 to 1*1 if we use kernel of 5*5 we need only one kernel so have to work on 25 values.
          5*5 to 1*1 if we use kernel of 3*3 we need two 3*3 kernels so 9+9 = 18 values.
          
    As the trend started growing for using the 3*3 kernels NVIDEA prepared optimised architecture so that 3*3 kernal perfrom 
    faster compared to other kernels so its always better to use 3*3 kernels.(yet to read about this )
