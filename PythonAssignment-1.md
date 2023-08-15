## Assignment Part-1
Q1. Why do we call Python as a general purpose and high-level programming language?
--> We call python is high -level programming language because it is very easylly
    understandable by humans.python is called general purpose because other than 
    application development and data science it is adopded by accounts and many other
    purpose to get it done.

Q2. Why is Python called a dynamically typed language?
--> python is called a dynamically typed language beacuse we dont initialise the 
    variable type during code writting. it automatically detect the data type 
    during runtime.

Q3. List some pros and cons of Python programming language?
  --> PROS= 
            -Firstlly it is a bignner friendlly Language.
            -it have very Extencive Library collection.
            - It highly Scalable.

     Cons->
            -It is slower than Compile language.
            -Security is lower than other language.
            -Pythone comes with high  memory consumtion.

Q4. In what all domains can we use Python?
 --> Pyhton is mainly popular for Machine learning and artificial intelligence
     and Data science.other than that it can be used for web devlopment,
     Gaming development,Application development.

Q5. What are variable and how can we declare them?
--> The name given to the sstorage is variable . Variables are those in which we 
    store items.Usully we declaire them with giving them the data type and assign
    some value but in case of python we did not give the data type to variable
   only assign some value to it . during runtime python get to that it is a variable.


Q6. How can we take an input from the user in Python?
--> The "input()" function is sed to take input in the python Like-
    A=int(input("Give  the first value:-"))
    B=int (input("Give the second value:-"))
    C=A+B
    print(C)

Q7. What is the default datatype of the value that has been taken as an input using
    input() function?
--> The default "input()" function return String.

Q8. What is type casting?
--> Converting one Varible data type to other is called type Casting Like->
    a =16
    a =float(a)
    print(a)
    
    output-16.0
    

Q9. Can we take more than one input from the user using single input() function?
    If yes, how? If no, why?
--> yes, there are two ways that in pythone we can take more that one input uing only
    single input() function . like->
   1- using split() function
   2- using list Comprehension 
 

ex- (i)-a,b,c =input("Give the values to variables:-").split()
       print(a)
       print(b)
       print(c)

    (ii)-x = list(map(int, input("Enter multiple values: ").split()))  
         print("List of students: ", x)  


Q10. What are keywords?
--> Keywords are those reserved words that can not be used for other purpose 
    that it is reserved for.Like-class, for,while,not not in, in etc. 

Q11. Can we use keywords as a variable? Support your answer with reason.
--> No, keywords cannot be used for other purpose than it is reserved for.

Q12. What is indentation? What's the use of indentaion in Python?
--> Indentation is the space given befor specific keyword that it shows that it is
    continuation of or inside another command.Usually it is 4 spaces but more can be
   used. like- 
               for x in list1:
                   print(x)

Q13. How can we throw some output in Python?
-->We can throw Output in a python with use of "print" keyword.
   ex- list2=["Apple","Banana","Cherry","Pen"]
       print(list2)

Q14. What are operators in Python?
--> Operators are those which is use to some calculation and operation between
    two or more numeric values.Like-> +,-,/,%,+=,-=,/=,%= etc
    ex- a=4
        b=2
        print(a+b)
        print(a-b)
        print(a/b)
        print(a%)
     

Q15. What is difference between / and // operators?
-->  "/" operator is divition operator it simply divide two numerical value and give the value and
     it can also give output as decimal.
     "//" operator is a Floor division operator which not only divides but give the minimum value after 
      divition it doesnt includes dicimal part.like-if normaloutput is 7.5 it will give only 7.

Q16. Write a code that gives following as an output.
```
iNeuroniNeuroniNeuroniNeuron

```
--> Name=input("Enter the name you want to provide:- ")

    input console=iNeuroniNeuroniNeuroniNeuron

                (or)

     a,b,c,d=input("Enter the name you want to provide:- ").split()
     print(a,b,c,d)
      
     In input console-
      a=iNeuron
      b=iNeuron
      c=iNeuron
      d=iNeuron

Q17. Write a code to take a number as an input from the user and check if the 
    number is odd or even.
--> CODE-
         num =int(input("Enter the number you want to check :-"))
         if(num%2==0):
             print("Number is even")
    
         else:
             print("Number is odd")

Q18. What are boolean operator?
--> Boolean operator are those which tell teh validity of statement 
     and it gives output like- True or False

Q19. What will the output of the following?
    ```
    1 or 0 -True

    0 and 0 -False

    True and False and True -False

    1 or 0 or 0 -True
    ```

Q20. What are conditional statements in Python?
--> Conditional statements are those by which we can provide conditons in the code.
    The keywords are used to provide conditions in the code are -if,elsea nd else.

Q21. What is use of 'if', 'elif' and 'else' keywords?
-->   'if', 'elif' and 'else' are the eywords which is used as conditional statement in 
      the code in python.
      like if we have written the code using these three keywords then the code will go like these
      first it will go to 'if 'statement if that statisfy the condion code will excicute if not satisfied
      the it will go to elif if that statisfy the condion code will excicute if not satisfied
      the it will go to else statement and finishes the code.

Q22. Write a code to take the age of person as an input and if age >= 18 display "I can vote". 
     If age is < 18 display "I can't vote".

-->  CODE=
     name=input("Enter name :- ")
     Age=int(input("Enter the Age:- "))
     if(Age>=18):
         print(name,"Can vote")
     else:
         print(name,"Can't vote")

Q23. Write a code that displays the sum of all the even numbers from the given list.
```
numbers = [12, 75, 150, 180, 145, 525, 50]
```
--> numbers = [12, 75, 150, 180, 145, 525, 50]
     new_list=[]

     for x in numbers:
         if x%2==0:
            new_list.append(x)
     print(new_list)

     print(sum(new_list))

Q24. Write a code to take 3 numbers as an input from the user and display the greatest no as output.
--> CODE->
    a=float(input("First value :-"))
    b=float(input("Second value :-"))
    c=float(input("Third value :-"))

    if(a>=b) and (a>=c):
        max=a
    elif(b>=a) and (b>=c):
        max=b
    elif(c>=a) and (c>=b):
        max=c
    print("Maximum value:-",max)


Q25. Write a program to display only those numbers from a list that satisfy the following conditions

- The number must be divisible by five

- If the number is greater than 150, then skip it and move to the next number

- If the number is greater than 500, then stop the loop
```
numbers = [12, 75, 150, 180, 145, 525, 50]
```
-->   num1 = [12, 75, 150, 180, 145, 525, 50]
      for num in num1:
          if num %5==0:
             if num >=150:
                 break
             print(num)



