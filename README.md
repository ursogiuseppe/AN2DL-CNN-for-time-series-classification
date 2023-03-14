# AN2DL-CNN-for-time-series-classification

* This is the second homework for the Artificial Neural Networks and Deep Learning course, Politecnico di Milano, academic year 2022-2023, prof. Matteucci Matteo.

* The goal of the project is to classify time-series among 12 classes, through a deep convolutional neural network. Therefore, being a classification problem, given in input a time series (of size 36x6, 36 time steps and 6 variables), the CNN outputs the predicted class label.

* For this homework the team has experimented with also FNN, LSTM, Bidirectional-LSTM and Transformer models, but they performed worse or as good as the final proposed solution. Therefore, the team decided to implement a CNN (with 1D convolutions), which leaded to the best performances (in terms of accuracy) despite model simplicity.

* The notebook is supposed to be run in a Kaggle environment.

* More details about the homework specification and approach to it in the [report](https://github.com/ursogiuseppe/AN2DL-CNN-for-time-series-classification/blob/main/GLM22_Report.pdf).

* The project was developed in a team, composed by me, Lorenzo Trevisan and Matteo Venturelli.
