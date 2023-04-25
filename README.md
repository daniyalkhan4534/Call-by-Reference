Actual parameters: The parameters that appear in function calls. Formal parameters: The parameters that appear in function declarations.


![image](https://user-images.githubusercontent.com/127819492/234354626-6a254ff0-0729-47d3-91ec-cdbf63fa9b0a.png)

The call by reference method of passing arguments to a function copies the address of an argument into the formal parameter. Inside the function, the address is used to access the actual argument used in the call. It means the changes made to the parameter affect the passed argument.

To pass a value by reference, argument pointers are passed to the functions just like any other value.

It shows that the change has reflected outside the function as well, unlike call by value where the changes do not reflect outside the function.

![image](https://user-images.githubusercontent.com/127819492/234354821-de20b8a1-dc8d-46eb-85d1-c3c1e0cfd6c5.png)
