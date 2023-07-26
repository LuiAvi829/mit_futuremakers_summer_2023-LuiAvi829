# Regression Loss Functions

## Topics covered in today's module
* Mean Squared Error
* Mean Absolute Error
* Mean Squared Logarithm Error

## Main takeaways from doing today's assignment
Mean Squared Error (MSE): This is the most commonly used loss functions when working with regression problems. It measures the average squared difference between the predicted values and the actual values and it penalizes larger errors more heavily than smaller errors. It does this with the following formula:

MSE = (1/n) * Σ(actual - predicted)^2
(n is the number of data points, actual represents the true target values, and predicted represents the predicted target values.)

Mean Absolute Error (MAE): This one is also used for regression problems, it measures the average absolute difference between the predicted values and the actual values. Errors are all treated equally, no matter how small or big the errors. The formula for MAE is:

MAE = (1/n) * Σ|actual - predicted|
(n is the number of data points, actual represents the true target values, and predicted represents the predicted target values.)

Mean Squared Logarithmic Error (MSLE): MSLE is more useful when working with data that has a wide range of values. It measures the average squared logarithmic difference between the predicted values and the actual values. The formula for MSLE is:

MSLE = (1/n) * Σ(log(1 + actual) - log(1 + predicted))^2
(n is the number of data points, actual represents the true target values, and predicted represents the predicted target values.) 

## Challenging, interesting, or exciting aspects of today's assignment
I found this assingment very interesting, studying  Mean Squared Error (MSE), Mean Absolute Error (MAE), and Mean Squared Logarithmic Error (MSLE). Although it presented some challenges initially, particularly in comprehending the underlying formulas for each metric, I found the experience to be very interesting.

## Additional resources used 
chatGPT for code errors, grammatical erros and some definitions.

LinkedIn article by Aishwarya B titled Regression Metrics - Of all metrics why MSE? (link: https://www.linkedin.com/pulse/regression-metrics-all-why-mse-aishwarya-b/) 
