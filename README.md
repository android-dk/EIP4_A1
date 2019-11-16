# EIP4

## Result of print(score) : [0.029410586557118222, 0.9926]

### 1. Convolution 
Mathematical operation that is performed on the input thereby transforming the input. This operation is performed in a way such that  the spatial relation of the pixels in an image is preserved.

### 2. Filters/Kernels
The object that performs the convolution on the input and extracts the output of that convolution. 

### 3. Epochs
When your training algorithm has seen the entire training data set, it is said to have completed an epoch.

### 4. 1x1 Convolution
It convolves on the channels (feature maps) to produce an output channel which has parts that are contextually linked to each other. 1 x 1 reduces the Z depth while Maxpooling reduces the X & Y size.

### 5. 3x3 Convolution
Standard size of your kernel. It is best odd size kernel to use because it has a left and right view, useful for edge detection.

### 6. Feature Map
Once a kernel traverses the entire input image, it creates a map of the outputs from its convolution operation on the image. 

### 7. Activation Function 
When we perform a convolution operation, we get a sum of the pixel values after each time the kernel traverses a part of the image. This number could be anything on the number line. The activation function converts this number such that it falls in the range of 0 to 1. 

### 8. Receptive Field
#### Global :
This is the number of pixels the network is looking at. We want this to equal the size of the image 
Eg : For a 128 x 128 image, we want the Global receptive field to be 128.

#### Local : 
It is simply the size of the kernel. 
