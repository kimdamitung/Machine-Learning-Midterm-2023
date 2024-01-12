Machine Learning Midterm 2023
(Data) Wine.data 
(0) three different cultivars(3種不同栽培品種) 
(1)Alcohol酒精百分比
(2) Malic acid
(3)Ash
(4) Alcalinity of ash 
(5) Magnesium
(6) Total phenols 
(7) Flavanoids
(8) Nonflavanoid phenols
(9) Proanthocyanins
(10)Color intensity
(11)Hue 
(12)OD280/OD315 of diluted wines
(13)Proline
Question:
(1A) After selecting a cultivar, 
    select any one of the attributes in (2)-(13) as the independent variable x, 
    (1) alcohol percentage as the dependent variable y, 
    use excel to create the predicted value of the linear regression and print it out chart
(1B) Use the same data in python and list the same results
(2A) Among the selected cultivars, 
    use the attributes of (2)-(13) to extract any two independent variables X1, 
    Only take out the first 12 pieces of data to make predictions
(2B) Using the same data, use python's multivariate regression to list the same predicted values and print out the chart (as shown below)
(3) Select the first 30 columns from the data in (1A) and save them as P, 
    so P is a list with 30 elements, 
    and each element is a list containing 2 elements.
    (a) Sort the key values of P based on the first row and reorder 
    (b) Convert P into a numpy array of float64 (30,2) and save it as Q (b) Add a full row after the last row of Q Make it (30,3) with a straight line of one and save it as R. 
    (c) Use the three straight lines of R as the values on the three axes of 3D and use matplotlib to draw 4 3D diagrams from different perspectives
