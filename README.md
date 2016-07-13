#Notes for Python 3 Sturdy
### Numerical Operation
1.**Exponentiation**
To raise one number to the power of another, use **double asterisks**
```
2**5=32
```
2.**Quotient & Remainder** 
To determine **Quotient & Remainder** in division, use **floor division** and **module**  operators, respectively.
```
20 // 6
3
1.25 % 0.5
0.25
```
**New Words**:
> Exponentiation
>: The operation of raising one quantity to the power of another.

>Quotient
>: A result obtained by dividing one quantity by another.
>
>Remainder
>: The number which is left over in a division in which one quantity does not exactly divide another:

### Strings
 A string is created by entering text **between two single or double quotation marks**.
```
print("Pain is inevitable, suffering is optional")
print('Look at the perfect side, now you have something to fix.')
```
Some characters can not be directly included in a string. For instance, double quotes can't be directly included in a double quotes string; this would cause it to end prematurely.

Characters like this must be escaped by placing a **backslash** before them. Other characters that need to be escaped are **newlines** and **backslashes**. Double quotes only need to be escaped in double quotes strings, and the same goes to single quotes strings.

Newlines can also be escaped by writing string with **three sets of quotes** and pressing ENTER when need newline.
```
print("This is a new\\n line")
print("""OK Google
Set a timer for 60 mins""")
print("Karel said 'Oh boy, Python is so hard to learn!'")
```


### Output & input
**Output**
Usually, programs take **input** and process it to produce **output**.
In Python, we can use **print function** to produce output, this displays a textual representation on the screen.
```
print(1+1)
print("Hello, Summer!")
```
**Input**
To get a input outcome from user, we can use **input function**. The input function will prompts the user for input, and return what they entered as string (with the contents automatically escaped)
```
input("What is your favorite \nAAA game?")
```
>'What is your favorite \\nAAA game?'



















    

	