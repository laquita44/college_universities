# college_universities

### Get_dummies() Section

#### Example.

<p>
Here is an example of how pd.get_dummies() work.
</p> 

![Get_Dummies() Part 1](https://github.com/samuelroiz/Predict_Credit_Risk/blob/main/Images/example_get_dummies_part_1.png) <p> The following data frame is named <i> preview_get_dummies </i> displays two non-numeric columns. </p>

<p>
  Then apply the get_dummies() code: <b> pd.get_dummies(<i> preview_get_dummies </i>) </b>
</p>

![Get_Dummies() Part 2](https://github.com/samuelroiz/Predict_Credit_Risk/blob/main/Images/example_get_dummies_part_2.png)

<p>
Now the <i> preview_get_dummies </i> data frame has numeric columns which means it meets the standards of machine learning models.
</p>

### Get Dummies Outcome
<p>
Apply the get_dummies() code to the data frame and the data frame ends up having a shape of thirty-four thousand two-hundred ninety-nine rows and forty-four columns.
</p>

![Get Dummies Outcome](https://github.com/samuelroiz/Charity_Funding_Predictor/blob/main/Images/get_dummies_data_part_1.png)

### Train and Test Data

#### How does train and test work and what is it doing to the data?

### Standard Scaler Section

#### How does the Standard scaler work and what is it doing to the data? 

<p> Standard Scaler has a formula, let's assume the formula is <b> z = (x - u) / s </b> where <b> z </b> is the scaled data, <b> x </b> is to be the scaled data, <b> u </b> is the average of the training samples, and <b> s </b> is the standard deviation of the training samples. The average or mean is the sum of all data points divided by the number of data points. In this case, <b> u </b> is going to add up all of the training samples divided by several training samples. The standard deviation formula starts by taking the given values and placing them in one column. Square each value and place them in a second column. Find the sum of all values in the first column and square it. The value is divided by the number of data points in first the column and called this number <b> i </b>. Find the sum of all values in the created second column. Once find the value, subtract it by <b> i </b>. The outcome will be divided by the number of data points minus one. Value leads to the <b> variance </b> of the sample and data. Finally, the variance will be square rooted leading to the value standard deviation of the data. 
</p>

#### Example of Standard Scaler
<p>
To demonstrate the algorithm and how it functions, consider the data set {1,2,3,4,5}. The data set consists of 5 one dimensional data points and each data point has one feature. Now apply the standard scaler() to the data. The data set becomes {−1.41,−0.71,0.,0.71,1.41}.
</p>

<p>
  The following example takes all of the data points and converts them to a closer range of 0 to 1. Standard scaler helps prevent outliers and keep the data closer to each other rather than gaps. 
  </p>

### Standard Scaler Outcome 

<p>
 Apply the standard scaler code to the dummies' data frame to demonstrate the algorithm and drive the data closer to each other. 
</p>

![Standard Scaler X Values](https://github.com/samuelroiz/Charity_Funding_Predictor/blob/main/Images/standard_scaler_data_part_1.png)

## Contributing

Please read [CONTRIBUTING.md](https://gist.github.com/samuelroiz/1af49ec9eea365bc845ba04c5071a976) for details on our code of conduct, and the process for submitting pull requests to us.

## Versioning

We use [SemVer](http://semver.org/) for versioning. For the versions available, see the [tags on this repository](https://github.com/your/project/tags). 

## Authors

* **Samuel Roiz** - *Data clean, Analyzed Data, Model* - [Profile](https://github.com/samuelroiz)
* 
* **LaQuita Williams** - *Model* - [GitHub](https://github.com/laquita44) 

* **Leo Lima** - *Data cleaned, API Keys, Model* - [GitHub](https://github.com/Leolima539) 

* **Kevin Perez** - *Model, Data cleaned* - [GitHub](https://github.com/KevinKVNPR) 

See also the list of [contributors](https://github.com/samuelroiz) who participated in this project.

## License

This project is licensed under the MIT License - see the [LICENSE.md](https://gist.github.com/samuelroiz/1af49ec9eea365bc845ba04c5071a976) file for details

## Acknowledgments

* Education
* Government Education
* USC Data Visualization
* CSUN Mathematics
