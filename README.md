<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <title>Car Price Prediction using Machine Learning</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            margin: 40px;
            line-height: 1.6;
            color: #333;
        }
        h1, h2 {
            color: #2c3e50;
        }
        table {
            width: 100%;
            border-collapse: collapse;
            margin-top: 15px;
        }
        th, td {
            border: 1px solid #ccc;
            padding: 10px;
            text-align: left;
        }
        th {
            background-color: #f5f5f5;
        }
        img {
            max-width: 100%;
            border: 1px solid #ddd;
            margin-top: 10px;
        }
    </style>
</head>
<body>

<h1>Car Price Prediction using Machine Learning</h1>

<p>
This project predicts the selling price of used cars using machine learning regression models.
The system learns from historical car data and estimates prices based on multiple features.
</p>

<h2>Project Files, Visuals & Tools</h2>

<table>
    <tr>
        <th>Item</th>
        <th>Description</th>
    </tr>
    <tr>
        <td><strong>car data.csv</strong></td>
        <td>Dataset containing car features such as selling price, year, fuel type, transmission, and owner details.</td>
    </tr>
    <tr>
        <td><strong>Car_prediction.ipynb</strong></td>
        <td>Main notebook with data preprocessing, visualization, model training, and evaluation.</td>
    </tr>
    <tr>
        <td><strong>Car Age vs Selling Price.png</strong></td>
        <td>Scatter plot showing relationship between car age and selling price.</td>
    </tr>
    <tr>
        <td><strong>Selling Price Distribution.png</strong></td>
        <td>Histogram showing distribution of selling prices.</td>
    </tr>
    <tr>
        <td><strong>Actual vs Predicted Car Prices.png</strong></td>
        <td>Comparison of actual prices vs model predictions.</td>
    </tr>
    <tr>
        <td><strong>Tools Used</strong></td>
        <td>
            Python, Pandas, NumPy, Matplotlib, Seaborn, Scikit-learn<br>
            Models: Linear Regression, Random Forest Regressor
        </td>
    </tr>
</table>

<h2>Visual Output</h2>

<h3>Car Age vs Selling Price</h3>
<img src="Car Age vs Selling Price.png" alt="Car Age vs Selling Price">

<h3>Selling Price Distribution</h3>
<img src="Selling Price Distribution.png" alt="Selling Price Distribution">

<h3>Actual vs Predicted Car Prices</h3>
<img src="Actual vs Predicted Car Prices.png" alt="Actual vs Predicted Car Prices">

<h2>Conclusion</h2>
<p>
The Random Forest Regressor performed better than Linear Regression by capturing non-linear patterns in the data.
This project demonstrates effective use of regression models, feature engineering, and data visualization.
</p>

</body>
</html>
