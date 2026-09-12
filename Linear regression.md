<h1> Linear Regression </h1>


<h4> Simple linear regression </h4>

            Simple linear regression models the relatoionship between 2 variables with a linear equation to observe data
             the equation used is 
              > y' = b + w1x1

              y' is the predicted label the output
              b is the y intercept , also the bias of the model
              w1 is the weight and x1 is the input

<h4> Target Variable </h4>
            
            The target variable is y which is like the actual target the true value
            ϵ = y - y' gives the value of how far the target is from the actual value

<h4> Misc </h4>

        Feature/Label is the x and y value and features are inputs and labels are the targetoutput

        Overfitting is when the model learns other stuff than the actual input
        > it can happen because of reasons such as : too many variables , not enough data , high variance

        Underfitting is when the model happens when the model is too simple and instead of curves the model draws a linear eqn graph
        > (ngl i didnt find anything abt this so im not sure if this part is correct)


        Prediction error occurs when there is a large margin of error and the predicted valeus are too far apart, which shows the model struggles to predict accurately.
    
        > so a model with high prediction error will usually have terrible Mean squared error/ mean absolute error


<h1> Case Studies </h1>

<h4> Using Linear Regression Analysis to Predict Energy Consumption </h4>

    > Reference : https://www.researchgate.net/publication/381955955_Using_Linear_Regression_Analysis_to_Predict_Energy_Consumption

    Researchers from vietnam have utilised linear regression to predict energy consumption in practical applications. Here they set up a predictive model using data from (IoT).

    They use the linear regression model for 3 case studies, they use features for predicted electricity consumption , Predicted consumption , and use labels Actual elecrricity consumption and Actual gas consumption
    
    then they compare the graphs. The models successfully identify the predictions really well with very high correlation coefficient. The graph for gas has higher MSE but accurate MAE.
   





## Review Status
Ready .
