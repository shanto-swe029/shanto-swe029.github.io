<a href = "https://shanto-swe029.github.io/"> <img src = "https://shanto-swe029.github.io/newgitphoto/home.png" height = "80" align = "left"> </a>
<a href = "https://shanto-swe029.github.io/programmingnotes"> <img src = "https://shanto-swe029.github.io/newgitphoto/programmingnotes.png" height = "80" align = "left"> </a>
<a href = "https://shanto-swe029.github.io/mathematicsnotes"> <img src = "https://shanto-swe029.github.io/newgitphoto/mathematicsnotes.png" height = "80"> </a>
<a href = "https://shanto-swe029.github.io/programmingproblems"> <img src = "https://shanto-swe029.github.io/newgitphoto/programmingproblems.png" height = "80"> </a>
<a href = "https://shanto-swe029.github.io/must-do-math-cp/home"> <img src = "https://shanto-swe029.github.io/newgitphoto/mustdomathforcp.png" height = "80"> </a>

***


# printf() & scanf() : Common Mistakes!

***

Let's remember this situation - our whole code is okay, but when I want to take input (in Codeblocks), our codes stop running and returns an error.
<br>
Let's remember another situation - we added `a = 10` with `b = 20` and stored in `c = a + b`. So output must be `30`. But when we run our code,
we see that the output is a `6 digit number` or it gives `0`!
<br>

Do they still happen in your life? Then this section is for you.
<br>

### Syntax of scanf() function

- `scanf("%DataType", &VariableName);`

    - If you mistakenly forget to put the `ampersand(&)` sign before the variable, your code will `crash` and will `terminate instantly`.
    If you face this sort of problem that your code is not taking input then do not panic and `check all the scanf() functions`.
    
    - But **if you are scanning a string, you must not use `ampersand(&)`!**

### Syntax of printf() function

- `printf("%DataType", VariableName);`

    - If you mistakenly use an `ampersand(&)` sign before the variable name, your code will print a 6 digit number which indicates the memory 
    position of the variable. This happens frequently when we copy a `scanf()` line and change the scanf to printf but forget to remove the 
    `ampersand(&)` signs. So, if this happens, do not panic and check all the `printf()` functions.
    
    - If you mistakenly use wrong `datatype`, your program may give a output `0` or anything can happen. But in most cases, I found 0. You can write 
    a code and run it to see the changes. But if this sort of things happen, check all `printf()` functions.


***

You may try to write some codes using these mistakes and see what happens. I would highly suggest you to do so. Because, if we do not make mistakes, 
we can never learn.
<br>

Let's try this yourself - **What happens when you use a wrong datatype in a scanf() function?**

***

## Happy Coding!

***

`This page is maintained by Ariful Islam Shanto`








