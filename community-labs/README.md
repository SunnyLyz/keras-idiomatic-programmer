# Labs for Community Participation in Research

This section contains labs that consist of a notebook and corresponding presentation for community participation in machine learning research. The audience for these notebooks are junior to mid-level data scientists.

| Lab | Description |
|-----|-------------|
| `AutoEncoder for CNN` | Research using lower dimensional encoded inputs to CNN (vs original image) |
| `Regularization` | Research using regularization to counter overfitting |
| `Ensemble` | Research using intra-model ensemnble methods |

### AutoEncoder for Convolutional Neural Networks

**Objective**

To replace a traditional "stem convolution group" of higher input dimensionality with lower dimensionality encoding, learned from first training the dataset on an autoencoder. Goal is that by using a lower dimensionality encoding, one can substantially increase training time of a model.

*Question:* Can one achieve the same accuracy as using the original input image?

*Question:* How fast can we speed up training?

### Regularization

**Objective**

To explore methods of regularization and learning rates to prevent the training data from "fitting" to the weights in a compact model -- without use of historical methods such as dropout or data augmentation.

*Question:* Can we generalize a compact model without image augmentation?

*Question:* How is training time effected?

*Question:* How small can a compact model be made and maintain accuracy on the validation/test data?

### Ensemble

**Objective**

To replace a traditional "inter-model" ensemble of models of high complexity with an "intra-model" ensemble of lower complexity, while retaining the performance benefits.

*Question:* Can one achieve the same performance with intra-model bagging vs. traditional inter-model ensemble?

*Question:* Can one achieve the same performance with intra-model stacking vs. traditional inter-model ensemble?