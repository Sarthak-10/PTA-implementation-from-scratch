# PTA-implementation-from-scratch

The .ipynb file contains the solution to the attached Problem Statement.The utils.py file contains the code for the Perceptron Training Algorithm and it is imported in the driver code. 

**About the Perceptron Training Algorithm (PTA)**

The Perceptron Training Algorithm was introduced by Frank Rosenblatt in 1943.

![image](https://user-images.githubusercontent.com/55259635/223987029-f8e326e3-eaf2-4bee-ac4f-c1a25b0dc60c.png)

The algorithm takes the data as input namely (x1,x2,...,xn) as the columns or features of the data.It then performs an affine combination of the data with the weights of the perceptron.There are various ways to initialize the weighs,one of them being Random initialization.After performing the affine combination the resulting weighted sum is passed on to a threshold function to obtain the output.

The function can be chosen from a range of activation functions.Here we will discuss about the sign function only.

![image](https://user-images.githubusercontent.com/55259635/223990334-d7a36e65-4919-4f92-b538-2128dde3f0dc.png)

If the weighted sum is above zero then the perceptron is said to activate and returns a 1, whereas if the weighted sum is less than or equal to zero then it returns a -1.
The above constitutes a forward pass of the Perceptron Training Algorithm.

![image](https://user-images.githubusercontent.com/55259635/223994541-b905a440-4adc-4687-9822-91f538a6be5e.png)

In the backward pass if the above error condition is met then weight update as described in the above image takes place.
