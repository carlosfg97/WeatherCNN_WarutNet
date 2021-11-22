# WeatherCNN_WarutNet

* Simple **Convolutional Neural Network**  architecture to predict the weather summary of the next day (Foggy, Breezy, Clear, Overcast, Mostly Cloudy, Partial Cloudy) based on a current day weather information. Data is pivoted into a matrix form (or panel data points) so the CNN is able to convolute across two dimensions and find local regions of relevant correlated information, similar to how an image processing would happen.

* **Fast training times** ( <60 seconds to fit 800K data points) using Tensorflow and Keras backend in a GPU-enabled Colab environment

* CSV file uploaded for reference
