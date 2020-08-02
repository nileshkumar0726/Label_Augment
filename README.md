# Label_Augment

Purpose: Regularize class labels with augmentation techniques.... For example if a normal image has 1.0 prob of ground truth then a brightened that detriorates the image somewhat should probably have probability of < 1.0.... 

Done
  - Notebook showing effect of different brightness factors on images
  - Trained a simple Conv net on Cifar
  - Modified Cross Entropy loss in pytorch to support one hot using [this](https://discuss.pytorch.org/t/how-should-i-implement-cross-entropy-loss-with-continuous-target-outputs/10720/18)

To Do 
  - Augment samples with brightness and change labels as well
  - Train same conv net with augmented examples
  - Read into different kind of classification losses other than cross-entropy
