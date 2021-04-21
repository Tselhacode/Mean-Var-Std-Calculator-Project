# Mean-Var-Std-Calculator-Project
A function that uses numpy to output the mean, variance, and standard deviation of the rows, columns, and elements in a 3 x 3 matrix.

I first imported the numpy library. I then created a function calculate with a parameter my_list which will be the input of list with 9 numbers. In order to make sure the list is none other than 9 numbers, I used error handling if... raise ValueError. 

I converted the list into a 1d numpy array and then converted that into 3d matrix which is also a numpy array datatype with the help of reshape attribute. 
I then calculated mean, variance, std, sum of the rows, columns, and elements in a 3 x 3 matrix. I used tolist() function to convert the arrays into list representation. 

I then created a dictionary which was later returned as an answer.

Instructions on how to run the code:

One can simply call the calculate function with a list input that has 9 numbers and print the output. 
