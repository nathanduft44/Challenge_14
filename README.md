# Challenge_14
# Original Model Performance
4 Day Short SMA, 200 Day Long SMA, training window(3 Months)
![Screen Shot 2021-10-02 at 8 54 35 PM](https://user-images.githubusercontent.com/86027898/135738945-cd030a85-3cf6-4316-b98b-44d9e722896a.png)

![Screen Shot 2021-10-02 at 5 09 26 PM](https://user-images.githubusercontent.com/86027898/135738571-065673cd-6757-4f4d-8c68-4ba38d9c6738.png)

Macro avg: 0.49, 0.50, 0.39
Weighted avg: 0.50, 0.55, 0.43

## Tuning tinkering
_To enhance a model it takes trial and error. The three tactics used in this notebook to tune the algorithm are : Adjusting Training Window, Use an Alternative ML Model, Adjusting techincal features_

## Tuned Model Metrics and Charts
2 Day Short SMA, 50 Day Long SMA, training window(6 Months)

![Screen Shot 2021-10-02 at 9 03 12 PM](https://user-images.githubusercontent.com/86027898/135739206-4bc7c314-07fe-4eaf-94a3-438b1113c829.png)

Random Forest Model: 4 Day SMA short, 100 Day SMA long, training period = 3months

![Screen Shot 2021-10-02 at 9 30 01 PM](https://user-images.githubusercontent.com/86027898/135739950-673aaff5-39dd-4400-892e-804e98c07571.png)

![Screen Shot 2021-10-02 at 9 30 52 PM](https://user-images.githubusercontent.com/86027898/135739964-23831a69-6388-443d-a489-b1619763ef5a.png)


## Tuning Results
What impact resulted from increasing or decreasing the training window?
After increasing the window the algorithm is not making as much profitable trades.

What impact resulted from increasing or decreasing either or both of the SMA windows?

Both it depends on the model your running and training window.

Did this new model perform better or worse than the provided baseline model? Did this new model perform better or worse than your tuned trading algorithm? The new Random Forest model outperformed both the Logistic Regression the Baseline Models.

