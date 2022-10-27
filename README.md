# LSTM-based-model-for-predicting-sales
I developed an LSTM model based on the tensorflow framework to predict the sales volume of electronic scales to help vendors better regulate their intake and reduce vegetable hoarding as well as waste.

# Problem Description
Vegetables in markets are likely to be in greater supply than demand, resulting in too many vegetables left over and extensive wasted. I imagine that if we could know the probable sales for the second day or the following days, the vendors would be able to reasonably regulate the amount of vegetables they need to sell everyday, reducing store and waste of vegetables.

We know that vegetable sales fluctuate mainly depending on seasons, weather, price and many other factors, and so far their impact on vegetable sales amount cannot be clearly defined. This is because sales prediction is highly non-linear, which requires prediction models to be able to deal with non-linearity and, as sales volume has a nature of time series, recurrent neural networks are suitable, for sales prediction.

# Model Select
The LSTM model is a special type of RNN model that solves the problem of RNNs not having long term memory.

# Input Parameter
Sales are influenced by time of year, weather, temperature and price. The input values are therefore defined as data, weather, temperature and price.

An interception of the data are shown in the table.

![image](https://user-images.githubusercontent.com/52540973/198298499-a3362b29-b6b3-490e-974b-ee1d40adcbce.png)


# Development
My develoment is based on TensorFlow library for training and implementing machine learning models. TensorFlow provides not only low-level machine learning building blocks, but also high-level Keras APIs for building neural networks. In my codes, the user can input data, weather, temperature and price and then the Python script will give a reasonable prediction value. 

The fit results for the training 500 times, and 5000 times are shown in Figure 1 and Figure 2 respectively.

![image](https://user-images.githubusercontent.com/52540973/198299219-df6fda00-bb56-4082-9cf9-51e225b73c88.png)

                                                 Figure 1. 500 training

![image](https://user-images.githubusercontent.com/52540973/198299266-3676ed69-bc84-4b3e-9f2a-ab3a8334689b.png)

                                                 Figure 2. 5000 training</center>

---

* The data cannot be uploaded due to confidentiality
