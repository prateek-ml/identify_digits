# Identify Digits (DataHack competetion)
One step further from sklearn datasets     One step towrads real datasets

Ah! The old n' familiar MNIST digit classification problem.
But here's a twist, we do not rely on Scikit-Learn for the dataset anymore, and tackle the problem using real images.

We trained our data on three models:
1. Logistic Regression (Test Accuracy : 91.60%)
2. Fully Connected Neural Network
3. Convolutional Neural Network


AND, we also added a script <code> custom.py </code> which will classify the image you provide

## How to Use
Just fork the repo, clone it in your working environment
Run the following command :
<pre>
<code>
custom.py -I "path-to-your-image" -M (optional) "model you want to choose"
</code>
</pre>

You can use the following arguments to choose your model:
- l (Logistic Regression)
- n (Fully Connected Neural Network)
- c (CNN, **default**)
