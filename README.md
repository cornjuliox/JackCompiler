# About this project
This is a compilation of the work I did for Coursera's Nand2Tetris class. I decided to consolidate everything into a single repository, clean it up, and present it as a porfolio piece that I can use when applying for jobs.

Unlike other repositories, I actually took the time out to learn how compilers are actually built (as in, I have a copy of the Dragon Book now) and have incorporated what I learned into the design of this final piece.

My goal for this project is to have a single compiler that can take properly-formed Jack code, and compile it down into valid Hack ASM that can be run in the official Hack emulators (i.e the ones they provide for the purposes of the course). Additionally it will also be able to compile down into the intermediate Hack Bytecode, as well as from Hack ASM to binary, in accordance with the course requirements. Finally, I'll do my best to include debug capabilities that would be useful for students, based on my own experiences with the course.

I'd like for others to be able to use this as a learning tool for their own studies, so I'm deliberately not going to write "clever" code, nor will I be erasing comments / annotations. 

# Features
- Jack to Hack VM Bytecode compilation (WIP)
- Jack to XML Syntax Tree (WIP)
- Hack VM Bytecode to Hack ASM compilation (WIP)
- Hack ASM to Binary (WIP)

With these three, this compiler should be able to generate most, if not all, of the output code for the course.