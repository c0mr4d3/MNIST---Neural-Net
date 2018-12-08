# MNIST---Neural-Net
A Neural Network made using pytorch to recongnize digits based on the training set from MNIST

# Running Instructions
Install Jupyter Notebook <br>
Execute the commands sequentially

# Side note
The names of the folders from the MNIST dataset have been changed from "training" and "testing" to "train" and "valid"
respectively to support the prebuilt NN from the fast.ai library used which is a further refinement of pytorch.

# Conclusion
The Model Achieves an accuracy of 97.3% in an image set of 10,000 images running 2 epochs with a learning rate of 0.01 
<br>
The learning rate was approximated using the method used in the paper "Cyclic Learning Rates for Training Neural Networks" by Leslie N. Smith

![Results](https://github.com/c0mr4d3/MNIST---Neural-Net/blob/master/result.png)

# End Note
The NN has huge scope of improvement by eliminating overfitting and running multiple epochs and experimenting with different learning rates. Any suggestions or PR's are welcome.
