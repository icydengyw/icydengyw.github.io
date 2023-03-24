## How to add a header to a matrix and write it to a csv or excel file?
We save the matrix using the format of `table` to combine various data types.
Related code:
```matlab
csvname='xxx.csv';
columns = {'A', 'B', 'C'};%Note that the number of rows in the A, B, and C matrices is the same, and each represents a column of data with different data types
data = table(A, B, C,'VariableNames', columns); % Create a table-type variable **data** based on these individual variables
writetable(data,csvname);%export to csv file
writetable(data,xlsname);%export to excel file
```
