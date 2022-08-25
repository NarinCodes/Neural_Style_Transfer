This project consists of two separate tasks—Binary Classification and Neural Style Transfer. Both tasks require the use of the CelebFaces Attributes (CelebA) dataset. For classification, the objective is to leverage deep learning to accurately determine whether a facial image is of a smiling individual or not. The ground truth labels for the response (i.e. smiling or not) are already annotated within the CelebA dataset. Two separate modeling techniques are explored—Custom CNN and Transfer Learning. The model architectures and performance metrics of both techniques are also analyzed.
For the second task, a facial image of Turkish actor Kenan Imirzalıoğlu is combined with Joe Reimer’s Waiting on Forever landscape painting through Neural Style Transfer. The content image of the Turkish actor belongs to the CelebA dataset. A different output image is generated via each of the two modeling techniques—direct use of VGG16 and VGG19 with transfer learning. The theory behind loss functions in neural style transfer is introduced, followed by a brief analysis of output images. Convergence values of the loss function are also compared.
The accuracy for classification using a custom model is 91.60% and the accuracy using transfer learning with VGG19 is 91.29%. For the style transfer task, the out-of-box VGG16 generated an image which did not contain painterly strokes and achieved a loss of 223. The transfer learning with VGG19 generated an image with better painterly style and improved color saturation, but lost some detailing of the facial structure. The style transfer loss in this case was 195.
