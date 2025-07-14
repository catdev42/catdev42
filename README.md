- 👋 Hi, I’m @catdev42
- 👀 I’m interested in C programming and Graphics programming!
- 🌱 I’m currently learning C and javascript/p5.js
- 💞️ I’m looking to collaborate on graphical projects, generative art
- 📫 How to reach me myakoven@student.42berlin.de
- 😄 Pronouns: she/her/sis
- ⚡ Fun fact: i am friendly

SIMPLEST INSTRUCTIONS FOR GDB (gnu debugger) IN TERMINAL:
1. Put this flag after cc or gcc: `-g` <br />
example: `cc -g main.c` <br />
this allows your program to have extra debugging information (`-g3` is also an option)
2. To launch the degubber with your program, type `gdb ./program`
3. If any warnings, just press enter until you can type in the terminal
4. Type this: `break main` <br />
this puts a place to stop in the program execution, a place from which you can take single steps. <br />
it can be shortened to "b main"
5. Type `run` <br />
this launches your program
6. Type `n` or `next` to take the next step in your program while staying inside the current function
7. Type `s` or `step` to step into a function that your are calling on the current line
8. Type `p` or `print` followed by variable name like `p i` or `p str[i]`.
9. If you have program arguments, launch the debugger like this: `gdb --args ./program_name arg1 arg2 arg3 ...`  
    Alt: just type in the arguments after the run keyword `run arg1 arg2`

EXTRAS<br />
10. Type `info local` to see the current value of all local variables <br />
11.  Type `info args` to see the value of all the argument variables that were passed into the current function <br />
12. Type `layout next` to see your source code in the terminal and press ENTER to iterate through different types of layout until you see one that you like. <br />
(my favorite is `lay src`) <br />
//have to check this//
13. Type `continue i = 3` in order to iterate the loop until a cetrain variable reaches an indicated value


You may have noticed that you can write many sommands as just 1 letter. 
<br />The debugger will let you know if it doesnt understand you.
<br />`q` for quit
<br />`run` to run again without quitting


<!---
catdev42/catdev42 is a ✨ special ✨ repository because its `README.md` (this file) appears on your GitHub profile.
You can click the Preview link to take a look at your changes.
--->
