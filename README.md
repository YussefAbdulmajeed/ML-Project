# ML_PROJECT
## Fashion MNIST

>👕 Fashion-MNIST is a dataset of [Zalando's](https://jobs.zalando.com/en/tech/?gh_src=281f2ef41us) article images—consisting of a training set of 60,000 examples and a test set of 10,000 examples. Each example is a 28x28 grayscale image, associated with a label from 10 classes. it was intend for Fashion-MNIST to serve as a direct drop-in replacement for the original MNIST dataset for benchmarking machine learning algorithms. It shares the same image size and structure of training and testing splits.

- you can find the notebook -> [code](Image_dataset/fashion.ipynb)
- The report of what we have done -> [report and model evaluation](Image_dataset/Fashion%20MNIST_report.pdf)
  
### Summary
- Representing the images in 3 ways
  - Pixel features representation (28×28) 784 pixel with a column for the label
  - HOG features  representation 70 features
  - PCA 40 features
  - Mix dataset between HOG and PCA
- Building Logistic Regression on each dataset Model hypertuning using GridSearch , Cross validation
- Kmeans (removing the label from the subset of dataset contain only 5 classses)
- Visualising K-means using PCA to create 3 components can be plotted as a 3D clusters
- Building a simpple GUI -> [GUI](Image_dataset/gui.ipynb)
  - you need to download the model from [model](mage_dataset/trained_models/LogisticRegressionPixel.pkl)

## House Pricing Regression
💡 House prices is regression data set about: Predict sales prices and practice feature engineering, RFs  of training set is  81 column and test set is  79 column .

Cleaning and Preparing the data

- Feature Selection
- Dealing with missing data
- Dealing with outliers
- Feature Encoding
- Model Building and Enhancing
    - Linear Regression
    - KNN Regressor
- you can find the notebook -> [code](House_Pricing/house_pricing.ipynb)
- The report of what we have done -> [report and model evaluation](https://hossam-ahmed.notion.site/House_pricing-5517e93ddb45425dbad2ca6a2b26ff84?pvs=4)
