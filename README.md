# Demo 2

All the things in the this world that you can do with a computer, but don't necessarily have to.
---
### Agenda:
1. Introductions (5 minutes)
   - Who are you? What do you do? Why are you here?
2. The Basics of Programming (30 minutes)
    - Write your name and a brief description of what you did today.
      *Note*: This is not code review! Just write something down.
3. Fun Activity (45 minutes)
     - Choose an activity from the list below and spend time doing it.
       - Drawing/Sketching
       - Coding a simple program (either a game or a utility)
         - You can use any language you prefer.
           - If you choose Python, make sure to bring a pen and paper so we can see what you wrote.
             - Don't worry if it doesn't work right away -- we will go over it together later.
       - Building something with Legos (or similar building blocks).
       - Playing a game (but please no violent games!)
7. Q&A Session (10 minutes)
8. Closing Remarks & Next Steps (5 minutes)

**List of Activities for Fun Activity Section:**
- Drawing/Sketching
- Coding a Simple Game [Python]
- Building Something with Lego Bricks
- Playing a Game (but please no violent games!)

---
### Demonstration Time! ###

I am HAKKI ABDELAZIZ, and I work as a software engineer.
let's  start by introducing ourselves. I am Andrew, and I teach at a local high school. Today, I am here to talk about programming and how you can get started on your own programming journey.
Today, I am going to show you how to write a simple program in Python.
This program will take two numbers as input from the user, add them together, and then print the result.
It's pretty straightforward stuff, but it demonstrates some important concepts like taking user input and using variables.
It's pretty straightforward stuff, but it'll give us a good starting point for our discussion today.

Here's my code:
python adder.py
python adder.py <number> <number>

If you run `adder.py` without any arguments, it will prompt you to enter two numbers.
Just type in the first number, press Enter, then type in the second number and press Enter again.
The program will then calculate their sum and display the result.
For example, if you type in 3 and 5, the output would be: 8
Now, let's talk about why this program works the way it does.
When we say "input" in programming, we mean that the computer waits for the user to provide some data.
In this case, we used the `<number>` syntax to indicate that the program expects one argument per command.
So when we ran `adder.py 3 5`, the program took those two numbers, added them together, and printed the result.
So when you ran `adder.py 3 5`, the program took those two numbers as separate inputs.
To get both numbers at once, we could have written `print(int(sys.argv[1]) + int(sys.argv[2]))`.
But instead, we used `sys.argv` which gives us access to all the command line arguments as a list.
We can ask for specific elements of that list using square brackets (`[]`), like `sys.argv[1]` and `sys.argv[2]`.
We can ask for specific elements by using square brackets (`[]`) like `sys.argv[1]` and `sys.argv[2]`.
By converting these strings into integers using `int()`, we can perform arithmetic on them.
Finally, we printed out the result using `print()`.
That's basically it!


---

### Questions? ###
what do u think about Ai?
how do u think coding is changing society?
do u prefer python or java?
if you were designing an app, what features would it need?
how do u think we can improve coding education?</s>