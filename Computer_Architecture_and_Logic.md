# Review of Ways to Design the Look of HTML Websites with CSS 
## (102 Read 06b: Discussion)

**What are Data Types?**
  Data Types tell the computer important information about a javascript variable that needs to be operated on. Remember that variables (var) are reanalyzed and adjusted each time the site loads, and can change due to different conditions. Below are different types of Data Types and their related operators and tools:

  - **Strings:** These are identified as content on a single line, placed between quotations, that follow a variable which begins the line of code and which display given the circumstances of the code.

    >String Example:
        >message = 'See our upcoming deals';
        >
            >Note: Don't forget to end the code with a semicolon!
            >Note: While you can use both single and double quotes for strings, it is recommended to use double quotes for html and single quotes for javascript.

  - **Numbers:** These are identified as a value or piece of content assigned to an identified symbol of the variable. This sounds more complicated than it is. Take a look:

    >Numbers Example:
        >var x = 16
        >(In the example, when x shows up in later code, it will be represented as the number 16. It is possible to also use other content instead, however:)

        >var x = "Volvo"
        >(In this example, when x is used in later code, it will be represented by the word Volvo.)

  - **Booleans:** These can have two values, such as true or false, or on or off.

  - **Arrays:** These are used in conjunction with the variable keyword to generate a list of content affected by that variable (and arrays can contain multiple other Data Types, by the way!)

    >Arrays Example:
        >var colors;
        >colors = ['white', 'black', 'custom'];

        >    Note: The content inside of the array, specified by the brackets, will be given display instructions later in the code.

  - **Assignment Operators:** These are symbols, used as tools in code, to assign values to javascript variables. We've already come across some of them, like =, +, -, and more.

  - **Conditional Operators:** Similar to Assignment Operators, but serve a unique function for larger and more complex Conditional Statements later in the teaching. ==, ===, <, and > are all conditional operators.

  - **Undefined:** A variable that has not been assigned a value (it is undeclared).

  - **Null:** Has exactly one value - null. This is the intentional absence of value. 

  - **Conditional Statements:** These, just like in the english language, are phrases used to change the display options on the website based on certain factors. if, else, and switch are all utilized to achieve this effect.

    >Conditional Statement Example:
    >   if (hour < 18) {
    >       greeting = 'Good Day!'
    >   }
    >
    >   Note: This examples declares that if the current time is of an hour less than the hour 18 (in military time), then the greeting Good Day! will be displayed on the site (did you notice the string data type used?).



# Additional Thoughts on How Computers Work
## (102 Read 06b: Discussion)

**What is a Computer?**
  A computer was designed as a machine or tool to assist with "thinking" problems. They were designed to serve four primary functions related to information: input, store, process, and output.

**How is Data Utilized to Make a Computer Run?**
  Let's start with the idea of a single wire. A wire can do one thing - transmit electricity or data, or some other important cargo. But it either does this...or doesn't. It is either on or off, yes or no, true or false (how very boolean). This is called a bit, a measurement of information. More wires = more bits = more information.

  The binary number system only has two digits, 0 and 1, and utilizes a multiplication table of 2 in order to represent larger numbers. For example, the number 9 would be represented as 1001. The last number would be multiplied by 1, the penultimate number would be multiplied by 2, the second number would be multiplied by 4, and the first number would be multiplied by 8.

    >(1x8) + (0x4) + (0x2) + (1x1) = 9 (in binary!)

  Though no one really does this, it's a good representation of the idea that any number can be represented in binary, or by how many wires you have working at any given point. 

  Additionally, text, sound, and even images and videos can be represented with numbers. Text can be represented by their numbered position in the alphabet, images and videos all have pixels that are represented by their color code, and vibrations in sound can be measured and represented by numbers.

**What are Circuits?**
  Circuits are made up of electrical components that can analyze input, and subsequently output, information. Circuits can change signals, combine them to create a new signal, and much more. Similar to how more wires can transmit larger numbers and amounts of information, so can circuits work together for more complex tasks.

**The Components of a Computer**
- Input: Many things can input data into a computer, such as a keyboard or a microphone. These convert the information into a binary language and send it to the computer.
- Memory: This, of course, is where the information is stored when it is not in use.
- CPU: The Central Processing Unit takes that information and interprets it to present in the format we need.
- Output: Things such as screens, speakers, and monitors display the calculated information in a format that we can inperpret ourselves.

**Hardware and Software**
  Hardware are the physical items inside of a computer, such as the circuits and chips. The CPU is the master chip of the computer (and you can have more than one!) that controls the circuits with commands.

  Software are the programs that tell the CPU what to do, and are powered with code. The Operating System tells the programs how to interact with the CPU. 

[Return to README](/README.md)