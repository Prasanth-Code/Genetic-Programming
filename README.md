# Genetic-Programming
Genetic Programming -> Symbolic Regression

Symbolic Regression is a technique to find mathematical relation among given parameters or variables.

So here is a basic symbolic regression python code to accompolish the task. 
It is intended to find the Newton's gravitational law which explain how much gravitational force (F) lies 
between two objects of mass m1 & m2 separated by distance r. i.e. F=(G m1 m2 )/ r^2


The text file "m1m2r.txt' contains 4 parameters i.e. 3 input variable (m1, m2 & r) and 1 target variable (F)
with 6351 instances. So if one feed these parameters into symbolic regressors, it should find the gravitational
law equation proposed by Newtons.

The saved symbolic regressor model "gravitational_law.sav" has already found the graviational equation through
training & uploading it here for reference.

If you wish to feed different parameters to find underlying mathematical relation among them, please modify the 
code accordingly.


You may need a computer with Juputer notebook & python 3
