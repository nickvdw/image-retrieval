# Image Retrieval

In this notebook, we will perform image retrieval with neural codes. We are applying the approach proposed in [1]. In particular, we train and evaluate a ConvNet on Tiny Imagenet. Then, we compute the outputs of intermediate layers for a new image dataset, which has not been used during training. These values serve as a representation, so-called neural codes for the new images. Then, we use the neural codes for image retrieval, by comparing the Euclidean distances between the codes of a query images and the remaining images. Finally, we evaluate the results both qualitatively and in terms of mean average precision.

[1] *Artem Babenko, Anton Slesarev, Alexandr Chigorin, Victor Lempitsky, "Neural Codes for Image Retrieval"*, ECCV, 2014. https://arxiv.org/abs/1404.1777.
