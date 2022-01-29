# Description: 
Identify the important activities of teacher which attempts the doubts the most.

DataFrame - Data of Teachers from different School Groups creating no of assignments, conducting tests, polls/quizes in live lectures, Classwork Added. All these Factors effect the number of doubts attempted by teacher to solve.

# DataSet: 
https://drive.google.com/file/d/19lWzDb1XudKSpa5gzDPxR9ty-rXyxo5-/view?usp=sharing

# Python Libraries Used: 
numpy,

pandas,

matplotlib,

seaborn,

warnings,

from sklearn.preprocessing import LabelEncoder  [Converting category labels into numerical using LabelEncoder]

from sklearn.model_selection import train_test_split 

from sklearn.linear_model import LinearRegression

from sklearn.linear_model import Ridge

from sklearn.linear_model import Lasso

from sklearn.ensemble import RandomForestRegressor as rfr


# Set up 
$ pip install numpy

$ pip install pandas

$ pip install matplotlib

$ pip install seaborn

$ pip install -U scikit-learn

# Conclusion

The highest doubts due to Classwork Added by teacher in lectures are in the Group B but the lowest are in the Group C.

Teachers of Group A generally add classwork more than teachers of the Group C, but people in the Group C have more Doubts attempted by gender than in the Group A and Group D overall.

And Teacher with quizes and polls tend to attempt higher doubts overall as well.

Classwork Added by teachers in the lecties is the most important factor. Classwork added has the highest impact on Doubts, even though the Doubts are growing with assignments, tests and polls/quizes. Also teachers who use polls/quizes generally add less classwork. 

Hence,
We will add more Classwork content in the library section of the platform so that the teachers can add the already content from the library itself.

Hence Teachers solving doubts will rise when the content added in live lectures will increase.
