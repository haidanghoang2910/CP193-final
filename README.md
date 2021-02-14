# Working code for optimization

Hi there! This is the github containing the working code for my portfolio optimization project. You will see two main code files: the Dashboard, and the model tests.

First, the Dashboard code is the back-end code for the website that I included in my project master article. I include the code here so you can play with it and maybe replicate it if you like. Various features are changeable, and you can find detailed explanations in the Technical model article. You will also find the requirements dashboard.txt file, which outlines the system requirements to run the code. Have fun!

Second, the model tests is the file that I worked behind the scene to test out several stock price prediction models to arrive at my choice of SVR. In the first section, you will find the implementation of 4 models I mentioned in the iterative work: Facebook Prophet, ARIMA, Random Forest, and Support Vector Regression. These implementations aim at estimating future stock prices. I used Google's stock prices. Each model is tested by splitting the data in a training set and a test set, then calculated the RMSE, MSE and MAPE. In the second section, you will find the same implementations but applied on two other stocks - this is to make our comparison and model choice more robust. As for interpretations of the result, I wrote up a (long) narrative of the project, and you can find it available HERE (include link when the final capstone is available in week 10). In the third section, you will find the Markowitz optimization - this section uses the prediction results from Random Forest (our chosen model).

In all sections, detailed explanations, in-line comments and docstrings are used to explain the rationales - please refer to them for more information.
