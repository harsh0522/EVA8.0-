ASSIGNMENT

Question

1 - Write a neural network that can:
    take 2 inputs:    
      1 - an image from the MNIST dataset (say 5), and
      2 - a random number between 0 and 9, (say 7)
      
      
2 - and gives two outputs:
      1 - the "number" that was represented by the MNIST image (predict 5), and
      2 - the "sum" of this number with the random number and the input image to the network (predict 5 + 7 = 12)
     
3 - you can mix fully connected layers and convolution layers
4 - you can use one-hot encoding to represent the random number input and the "summed" output.
      Random number (7) can be represented as 0 0 0 0 0 0 0 1 0 0
      Sum (13) can be represented as:
      0 0 0 0 0 0 0 0 0 0 0 0 0 1 0 0 0 0 0
      0b1101 (remember that 4 digits in binary can at max represent 15, so we may need to go for 5 digits. i.e. 10010
5 - Your code MUST be:
    well documented (via readme file on GitHub and comments in the code)
    must mention the data representation
    must mention your data generation strategy (basically the class/method you are using for random number generation)
    must mention how you have combined the two inputs (basically which layer you are combining)
    must mention how you are evaluating your results 
    must mention "what" results you finally got and how did you evaluate your results
    must mention what loss function you picked and why!
6 - training MUST happen on the GPU
7 - Accuracy is not really important for the SUM
8 - Once done, upload the code with short training logs in the readme file from colab to GitHub, and share the GitHub link (public repository)



