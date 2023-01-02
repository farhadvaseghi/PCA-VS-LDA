
# Principal Component Analysis(PCA) vs Linear Discriminant Analysis(LDA)

<p align="center">
<kbd>
   <img align="center" src="https://user-images.githubusercontent.com/54831801/210219318-ef0a904b-80bd-4956-87fe-2f7ebcd89886.jpg" width="500" height="400">
</kbd>
</p>

## PCA
- Principal component analysis, or PCA, is a dimensionality-reduction method that is often used to reduce the dimensionality of large data sets, by transforming a large set of variables into a smaller one that still contains most of the information in the large set.
- Reducing the number of variables of a data set naturally comes at the expense of accuracy, but the trick in dimensionality reduction is to trade a little accuracy for simplicity. Because smaller data sets are easier to explore and visualize and make analyzing data much easier and faster for machine learning algorithms without extraneous variables to process.
- So, to sum up, the idea of PCA is simple — reduce the number of variables of a data set, while preserving as much information as possible.

## LDA

- Linear Discriminant Analysis, or LDA, is a linear machine learning algorithm used for multi-class classification.
- Linear Discriminant Analysis seeks to best separate (or discriminate) the samples in the training dataset by their class value. Specifically, the model seeks to find a linear combination of input variables that achieves the maximum separation for samples between classes (class centroids or means) and the minimum separation of samples within each class

## PCA vs LDA: What's the Difference?¶
- Both PCA and LDA are linear transformation techniques. However, PCA is an unsupervised while LDA is a supervised dimensionality reduction technique.

- Unlike PCA, LDA tries to reduce dimensions of the feature set while retaining the information that discriminates output classes. LDA tries to find a decision boundary around each cluster of a class