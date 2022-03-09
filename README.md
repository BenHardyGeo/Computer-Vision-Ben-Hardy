# Computer-Vision-Ben-Hardy
Keywords: Computer Vision, Convolutional Neural Network, Classification, Supervised Learning

This notebook applies computer vision to classify seedling images into 12 different seedling types.

This notebook was prepared for the eighth project of the Post Graduate Program in Artificial Intelligence and Machine Learning: Business Applications from the McCombs School of Business at The University of Texas. Colour images were provided as tensors in a .npy (numpy file), while the labels were provided in a .csv file. The notebook was created and run in Google Colab but needed to be submitted as a jupyter notebook file. Unfortunately the input data are too large to upload to github. However the notebook appears to be viewing just fine.

The notebook contains useful code for viewing the images. It also contains code for finding an average image per seedling type, it wasn’t particularly useful in this case but might be useful to someone reading this.

Various techniques are applied to the input data to attempt to improve classification performance: Gaussian Blurring, Greyscaling and Image Data Augmentation. It was this last technique, which synthetic increases the number of testing images that had the biggest impact on the classification performance.

In terms of the Convolutional Neural Networks, I attempted many different architectures adding the number of layers, MaxPooling layers and dropout. In this case it had little effect on the classification performace, the input data was the limiting factor. Seedlings that were unique looking were very well classified. Seedlings that looked similar to other species were confused. If we removed the two most confused species (Black-grass and Loose Silky-bent) then the average accuracy increased from 86% to 90%

While this project was done as part of a school project. I believe it indicates the quality of work that I’m capable of in real-world applications. I was the top student in my cohort with a final course weighted average of 99.39%.
