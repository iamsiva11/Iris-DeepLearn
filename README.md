##Deep learning with Iris Dataset


The iris flowers dataset is a well studied and is a good problem for practicing on neural networks because all of the 4 input variables are numeric and have the same scale in centimeters. Each instance describes the properties of an observed flower measurements and the output variable is specific iris species.

The attributes for this dataset can be summarized as follows:

1. Sepal length in centimeters.
2. Sepal width in centimeters.
3. Petal length in centimeters.
4. Petal width in centimeters.
5. Class.

This is a multiclass classification problem, meaning that there are more than two classes to be predicted, in fact there are three flower species(virginica,versicolor,setosa).

This is an important type of problem on which to practice with neural networks because the three class values require specialized handling.

Below is a sample of the first five of the 150 instances:

>5.1,3.5,1.4,0.2,Iris-setosa
>4.9,3.0,1.4,0.2,Iris-setosa
>4.7,3.2,1.3,0.2,Iris-setosa
>4.6,3.1,1.5,0.2,Iris-setosa
>5.0,3.6,1.4,0.2,Iris-setosa


Dataset - Iris.csv

###Run:

>Keras (theano Babkend)

python iris-keras.py

>Tensor flow
python iris-tf.py

