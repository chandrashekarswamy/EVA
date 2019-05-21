#1. How many layers,
Based on CPU/GPU requirements we need to decide how many parameter we can use. 
Based on number of parameters and the accuracy (usecase) we can decide the number of layers.

#2. MaxPooling,
We can think of MaxPooling when we want to reduce the number of channels, this inturn reduces the parameters as well

#3. 1x1 Convolutions,
Merging the similar features and create the complex channels, we use this to reduce the number of channels currently, it needs less computation an less parameters

4. 3x3 Convolutions,
Best and Optimal Kernal, feature extractor.

5. Receptive Field,
this will give total number of pixels that our kernels have covered. 
ex: If we use two 3*3 kernels then Receptive fields = 5*5 

6. SoftMax,
Activation function which will exaggerate the output.

7.Learning Rate,

8. Kernels and how do we decide the number of kernels?
lesser the kernal size lesser the number of parameters we use.
even number kernal can not be symmetrical so we use odd number kernels.
3*3 is the most optimal one.

9. Batch Normalization,
it will increase the depth of the bright pixel to max depth of that layer and decrease the depth of dark pixel to min depth found in that layer

10. Image Normalization,

11. Position of MaxPooling,
min 2 layers away from the final/decisition makeing layer, and also maxpooling should be applied atleast after 3 layers of convolution.

12. Concept of Transition Layers,
MaxPooling + 1*1

13. Position of Transition Layer,
After we reach receptive fields of atleast 7*7 in small images ex: 28*28 and atleast 11*11 in case of big images ex: 400*400

14. Number of Epochs and when to increase them,
increase in number of Epochs will increare the accuracy to certain extent then it reach a max accuracy and reduce again.

15. DropOut
To reduce the over fitting, 

16 When do we introduce DropOut, or when do we know we have some overfitting
To bring down the difference between training accuracy and validation accuracy.
High training accuracy and low validation accuracy = overfitting

17. The distance of MaxPooling from Prediction,
minimum 2 layers

18. The distance of Batch Normalization from Prediction,
one 

19. When do we stop convolutions and go ahead with a larger kernel or some other alternative (which we have not yet covered)
when our image is 7*7 or less as our kernel will cover some pixels more time than others. 

20. How do we know our network is not going well, comparatively, very early
comparing the for out put of forst two Epochs

21. Batch Size, and effects of batch size
number of images that we test before back propagetion.

22. When to add validation checks
when we want to see which epoch will give better result.

23. LR schedule and concept behind it

24. Adam vs SGD
