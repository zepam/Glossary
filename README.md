# Glossary

Here, we collect definitions of important concepts

**Features**: A 'feature' is any attribute of a dataset that represents (tangible or intangible) information about it. The term can be used broadly whereever relational properties about the dataset are relevant or represented as values, series, matrices, etc.. As such, a feature could be a single datapoint, a measurement series, a statistical property of the data (or a subset thereof), a pattern in the data represented by a 'filter,' a weight or bias, etc. In linear algebra terms, a feature is representable as a dimension of a subspace of the vector space of the data.

**Random forest**: A machine learning algorithm for classification, regression and other tasks that operates by constructing a multitude of decision trees (during training) to generate a single result.

**Data dimensionality**: Dimensionality of data refers to the number of properties or categories in a dataset

**Regression Analysis**: Statistical processes for estimating the relationships between a dependent variable and one or more independent variables.

**Black box**: The inability to undestand how a deep learning system makes its decisions.

**Deep Learning**: neural networks with multiple layers, allowing complex patterns and representations to be learned from large datasets.

**Signal** The part of the data you want to study/explore. Datasets must sometimes be denoised in order to pull out what you want.

**Local model interpretation:** set of techniques aimed at evaluating why a model makes a specific prediction and what effect a specific feature value has on the prediction. 

**Data Mining:** Analyzing raw data to extract useful information and find patterns.

**Structured Data**: data organized in a specific format, such as position (lat, long) information or physical measurements.

**Unstructured Data**: data that are not organized in a specific format and require more complex methods for automated interpretation. Examples include images, papers, books, audio files etc.

**Data modality:** The simplest structure in which your data can be described (e.g., row-column, multi-dimensional, raster/image). 

**K Means Clustering** A machine learning algorithm for grouping variables that partitions the signals of interest by their behavior/patterns. This is an example of an unsupervised machine learning model. 

**Logistic Regression:** A statistical model used for classification given a dataset. Provides a discrete output.

**Node:** refers to computing unit a single CPU with multiple cores, a dedicated memory, and a dedicated storage. Terminology used in high performance computing (HPC).

**Instance:** refers to a computing unit, like a node. Terminology used in Cloud.

**Core:** a processing unit of a CPU or GPU that performs the tasks.

**Dimensionality Reduction:** A data transformation technique where high-dimensionality data is converted to lower-dimensionality data while preserving as much meaningful structure in the data as possible to address the curse of dimensionality and improve data visualization, interpretation, clustering, and other processing (ex. machine learning). 

![image](https://github.com/UW-ESS-DS/Glossary/assets/56406566/7477fad4-895e-4a42-97b6-40b3bcc2bf0a)

**Feature Engineering:** Manipulating raw data to select specific features from within the data.  Also referred to as feature extraction or feature discovery.  A feature, sometimes used interchangably with the term variable, can be a characteristic, property, attribute, etc. within the raw data.

**Deep Learning:** A subfield in machine learning based on artificial neural networks in which multiple layers of processing are used to extract progressively higher level features from data.

**Cross-Validation:** This involves splitting of your data into smaller groups to train and test your model. It helps check how well your model works on different data and prevents it from overfitting.

**Overfitting:** It occurs when a model learns to perform exceptionally well on the training data but struggles to generalize its performance to new, unseen data.

**Underfitting:** Occurs when a machine learning model is too simple to capture the underlying patterns in the training data, resulting in poor performance on both the training and testing data.

**Auto-encoders:** Neural networks that can efficiently compress and encode data, and then use that encoding to reconstruct the original data as accurately as possible, which can reduce the input data dimensionality. 

**Noise:** In the collected data noise is anything that is unwanted or adds difficulty for the model to interpret within said data.

**Convolutional Neural Network:** a deep learning algorithm that takes an input image and assigns weights to be able to diferrentiate other images from each other.  

**Hyperparameters:** Common in Bayesian statistics, they are values to control the learning process and the outcome values of the machine learning training algorithm.

**Resampling:** The process of repeatedly generating new samples from training data in order to understand uncrertenties in the data being used.

**Bootstrapping**: Bootstrapping is a resampling technique in statistics where multiple random samples are drawn with replacement from a single dataset. This method is employed to estimate the sampling distribution of a statistic and assess its variability.

**Data Augmentation**: Data augmentation is the process of generating new, artifical data from existing data. This is commonly used to increase the size of a training dataset in ML (ie. rotating input images in a data segmentation pipeline)

**Fuzzy Logic** : A logic system often used in machine learning, where results can be on a spectrum from correct or wrong, rather than entirely one or the other. Fuzzy Logic is particularly well-suited for use with noisy data.

**Neural network**: Is a computational model that mimics how the human brain works, using layers of connected nodes (or neurons) to learn from data and perform tasks like recognizing patterns and making predictions.

**Contrastive Learning**: A deep learning technique where similar patterns detected in the data are pushed close together in a representation space, while dissimilar patterns are pushed far apart.

**Activation Function**: A user-implemented function that provides a nonlinear learning aspect of an algorithm between inputs and outputs.

**Clustering**: An unsupervised ML method that groups unlabelled data together by finding how similar/different different pieces of data are to each other. 

**Gradient Descent**: An optimization algorithm used to minimize the loss function in machine learning models by iteratively adjusting the model parameters in the direction of the steepest descent of the loss function.

**Benchmark Dataset**: A dataset or data archive which is used to train the algorithm in machine learning.

**Physics-Informed Neural Networks**: Training of a neural network that is physis-agnostic at initial design, but constraining the predictions to obey physical law by crafting the loss function accordingly.

**Synthetic Data**: Data often used for training a model, generated by a computer and made to resemble real-world datasets. They can be helpful for creating data in cases where data is sparse.

**Kernel methods**: ML algorithms that use functions called kernels to project data into higher dimensional space. They are especially useful for pattern analysis of data that is not linearly separable. 

**Big O notation**: A mathematical concept used in computer science to describe the performance or complexity of an algorithm's runtime or memory usage as the input size (denoted as n) becomes large.

**Batch Normalization**: In deep learning, each step (or batch) of model training must be normalized to have zero mean and unit variance. This prevents numerically large features from dominating the training process.
