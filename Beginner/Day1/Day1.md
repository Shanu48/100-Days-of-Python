# Day 1

The first question that comes to mind is, what editor to use to start with the coding.

On **day 15** we will learn how to install and setup PyCharm which is the most popular local python code editor.

Till then we will be using **Replit**, a browser based code editor. This has a number of advantages:
1. We can get up and running immediately, with less time wasted on setup and troubleshooting, more time learning to code.
2. It's accessible anywhere, any computer/iPad/phone that's connected to the internet can be used to code.
3. Your code and progress are saved, ready for you to review and revisit at any time.
4. It's free.


## Getting started with Replit

1. Start by signing into [Replit](replit.com)
2. Once you are signed in, go through the small tutorial that the website gives to familarize yourself with the platform.
3. Create a new repel with python as the template.
4. Now write `print("Hello World!")` in the left hand side window. This is the first python program we have written. Click `Run` to see the output on the console.

     ![image](https://github.com/user-attachments/assets/919a405a-5db3-4719-9498-0120d72a6450)

## print() Function
This is the first function that we learn. Whatever we write in the parentheses is printed to the console. 

Any text that has to be printed needs to be enclosed in quotation marks `' ' or " "`

Anything that is included within the quotation marks is known as string. It makes sure that the editor knows that whatever is inside the quotation marks is not a part of the code. Its a string that we wish to print as it is.

Example:
```
Input:
  print("Hello World")
Output:
  Hello World

Input:
  print(Hello World)
Output:
  Error
```

There are time when we need to **print** the double quotes but the compiler confuses them with the start and ending of string. To avoid such confusion, we put a `\` before such symbols

Example:
```
Input:
print("I say "How are you?"")
Output:
Error

Input:
print("I say \"How are you?\"")
Output:
I say "How are you?"
```

Another way to avoid such confusion for the editor is to use single quotes `''` to write the code and then you can use the double quotes `" "` within the string or the other way round
Example:
```
Input:
print('I said "How are you?"')
Output:
I said "How are you?"

Input:
print("I said 'How are you?'")
Output:
I said 'How are you?'
```

You must have noticed that, to write something on the next line, you need to write the print function again. 

But, that is not necessary. It can all be written using a single print statement. Just put in `\n` character where you want to move to the next line. Another way  to do the same is to use triple quotations `''' ''' or """ """`. When you write a string in triple quotations, the editor will print the text the same way you have written, i.e., wherever you go the the next line and write, it will write in the same way

Example:
```
Input:
  print("Hello World")
  print("Hello World")
  print("Hello World")
Output:
  Hello World
  Hello World
  Hello World

Input:
  print("Hello World\nHello World\nHello World")
Output:
  Hello World
  Hello World
  Hello World

Input:
  print("""Hello World
  Hello World
  Hello World""")
Output:
  Hello World
  Hello World
  Hello World
```

