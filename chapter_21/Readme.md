**What is your shell set to?**

    env | grep SHELL
    SHELL=/bin/bash


**What directory are you in (don't use pwd this time)?**

    env | grep PWD
    PWD=/Users/WhiteWolf/workspace/davinci_coders_t3_2015/in_class/homework/learn_command_line_exercises/chapter_21

**What is your home directory set to?**

    env | grep HOME
    HOME=/Users/WhiteWolf

**Can you set your environment to have DEBUG set to true?**

    (master) David Jarrett
    nonames-air:chapter_21 $ export DEBUG="true"
    
    (master) David Jarrett
    nonames-air:chapter_21 $ echo $DEBUG
    true
