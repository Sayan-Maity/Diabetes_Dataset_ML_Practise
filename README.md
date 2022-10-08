 ## All the different kinds of small ML practise projects are collected and pushed in this repo !
 ### 1. main : 
 Diabetes Dataset on ML Practise \
 
 ### 2. main2 : 
 
 
 ### 3. classifier1 : 
 Classifier Problem on ML Practise :

<table>
<tr>
<td>
 Originally used as an example data set on which Fisher's linear discriminant analysis was applied, it became a typical test case for many statistical classification techniques in machine learning such as support vector machines
</td>
</tr>
</table>



 ```
from sklearn.datasets import load_iris

iris = load_iris()
iris
```
This code gives:

```
{'data': array([[5.1, 3.5, 1.4, 0.2],
                [4.9, 3. , 1.4, 0.2],
                [4.7, 3.2, 1.3, 0.2],
                [4.6, 3.1, 1.5, 0.2],...
'target': array([0, 0, 0, ... 1, 1, 1, ... 2, 2, 2, ...
'target_names': array(['setosa', 'versicolor', 'virginica'], dtype='<U10'), 
...}
```
