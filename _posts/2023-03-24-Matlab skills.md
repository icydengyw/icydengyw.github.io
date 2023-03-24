## How to add a header to a matrix and write it to a csv or excel file?
We save the matrix using the format of `table` to combine various data types.
Related code:
```matlab
%% Method 1
csvname='xxx.csv';
columns = {'A', 'B', 'C'};%Note that the number of rows in the A, B, and C matrices is the same, and each represents a column of data with different data types
data = table(A, B, C,'VariableNames', columns); % Create a table-type variable **data** based on these individual variables
writetable(data,csvname);%export to csv file
writetable(data,xlsname);%export to excel file
%% Method 2
A=[1 2 3;4 5 6]
T = array2table(A)%arrat to table
T.Properties.VariableNames(1:3) = {'x_axis','y_axis','z_axis'}%note the number of cols
writetable(T,'file.csv')
```
Ref:
> https://ww2.mathworks.cn/matlabcentral/answers/281150-writing-a-matrix-with-header-into-a-csv-file
> https://www.zhihu.com/question/39707220
