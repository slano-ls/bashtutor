--- TO-DO ---
signal handling of Ctrl-C, etc
make in-file functions static? does this make it faster?
error-checking
-------------

Below is the structure for containing information text for explanations

<<directory structure>>
bashtutor.c
Makefile
info/chapter_01.h
    /chapter_02.h
        extern char *chapter_02[]
    /chapter_03.h

    /chapter_01.c
    /chapter_02.c
        char *chapter_02[] = {"one" , "two", "threee"};
    /chapter_03.c

<<info/chapter_02.h>>
extern char *chapter_02[];

<info/chapter_02.c>
char *chapter_02[] = {
"(200) first one\n",

"(201) The \"ls\" command is greatly useful for a few things: \n \
    - list directories\n \
    - list files\n \
    - multiple options\n"
};
