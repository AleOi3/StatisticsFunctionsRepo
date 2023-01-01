# Description
This code apply some statistcs features like:

<ol>
    <li> Average</li>
    <li> Maximum</li>
    <li> Minimum</li>
    <li> Amplitude</li>
    <li> Median</li>
    <li> Quartil</li>
    <li> Linear Regression</li>
    <li> Plot in scatter mode</li>
    <li> Plot Histogram</li>
    <li> Calculate Correlation (Pearson)</li>
</ol>

Given a dataframe data.

To use this code you need use folowings packages:
<ol>
    <li> pandas</li>
    <li> numpy</li>
    <li> matplotlib</li>
    <li> math</li>
    <li> datetime</li>
</ol>

You can see this line in code:

%config Completer.use_jedi = False

It only affects how jupiter-notebook linting understanding.

You can see that I've created a generic DataFrame with columns: ['Date', 'Value', 'Value2']. The code has a class named StatistcsCalculator that allow the user to calculate the previously mentioned features passing this DataFrame. 

dataframe = pd.DataFrame([
    [datetime(2019,1,20), 215, 1],
    [datetime(2019,2,20), 480, 1],
    [datetime(2019,3,20), 325, 1.5],
    [datetime(2019,4,20), 550, 2],
    [datetime(2019,5,20), 920, 3],
    [datetime(2019,6,20), 670, 3],
    [datetime(2019,7,20), 825, 3.5],
    [datetime(2019,8,20), 1070, 4],
    [datetime(2019,9,20), 1350, 4.5],
    [datetime(2019,10,20), 1215, 5],
],columns=['Date', 'Value', 'Value2'])


