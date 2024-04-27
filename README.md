- 👋 Hi, I’m @catdev42
- 👀 I’m interested in C programming and Grphics programming!
- 🌱 I’m currently learning C and javascript/p5.js
- 💞️ I’m looking to collaborate on graphical proejcts, generative art
- 📫 How to reach me myakoven@student.42berlin.de
- 😄 Pronouns: she/her/sis
- ⚡ Fun fact: i am friendly

SIMPLEST INSTRUCTIONS FOR GDB (gnu debugger) IN TERMINAL:
1: Put this plag after cc or gcc: `-g`
(this allows your program to have extra debugging information)
2: If any warnings, just press enter until you can type in the terminal
3: Type this: `break main`
(this puts a place to stop in the program execution, a place from which you can take single steps.
this can be shortened to "b main")
4: Type `run`
(this launches your program)
5: Type `n` or `next` to take the next step in your program while staying inside the current function
6: Type `s` or `step` to to into a function that your are calling on the current line
7: Type `p` or `print` followed by variable name like `p i' or `p str[i]`

/* EXTRA */
8: Type `info local` to see the current value of all local variables
9: Type `info args` to see the value of all the argument variables that were passed into the current function
10: Type `layout` to see your source code in the terminal and press ENTER to iterate through different types until you see one that you like.
(my favorite is `lay src`)
You may have noticed tha tyou can write many sommands as just 1 letter. The debugger will let you know if it doesnt understand you.
`q` for quit
`run` to run again without quitting


<!---
catdev42/catdev42 is a ✨ special ✨ repository because its `README.md` (this file) appears on your GitHub profile.
You can click the Preview link to take a look at your changes.
--->
