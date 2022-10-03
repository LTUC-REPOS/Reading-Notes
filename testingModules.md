# Testing and Modules


<br>

## TDD With Python 

<br>


<p> 

1. Unit tests are some pieces of code to exercise the input, the output and the behaviour of your code. <br>

2. The tests can be considered as your alive documentation <br>

3. The test file name should follow the same name of module name with test_xxxx.py <br>

4. A convention widely used in the TDD enviroment is the AAA: Arrange, Act and Assert <br>

>  Arrange: you need to organize the data needed to execute that piece of code (input) 

<br>

> Act: here you will execute the code being tested (exercise the behaviour) 

<br>

> Assert: after executing the code, you will check if the result (output) is the same as you were expecting <br>


5. When we are writing tests we are forced to think about the design first and how we can break it into small pieces. <br>


6. TDD reduces the chances of having bugs in the production code <br>

</p>

<br>


##  if __name__ == “__main__”

<br>


<p> 

1. A module is a file containing Python definitions and statements. The file name is the module name with the suffix .py appended <br>

2. The variable __ name __ for the file/module that is run will be always __ main __  .But the __ name __ variable for all other modules that are being imported will be set to their module's name. <br>


3. Any code before the if else __ name __ will always run <br>

4. Imported modules will always run the else block because the __ name __ will be the file name  <br >

5. Python files can act as either reusable modules, or as standalone programs <br>


6. The __ name __ will be set to main only if the file was run directly <br>


</p>

<br>

##  Introduction to Recursion

<br>

### What is Recursion? 

<br>

> The process in which a function calls itself directly or indirectly is called recursion <br>

> The function containing recursion is called recursive function <br>

> The recursive function uses LIFO (LAST IN FIRST OUT) Structure just like the stack data structure <br>

> It keeps running until it reaches the base case <br>

### Why we need Recursion?


<br>

> an amazing technique with the help of which we can reduce the length of our code and make it easier to read and write  <br>


> We use Recursion when a task that can be defined with its similar subtask <br>


### When stack overflow error occuers? 

> The stack overflow error occuers when the stack memeory which preserive the functions calls reach it limits ( Deep recursion).








<br>

