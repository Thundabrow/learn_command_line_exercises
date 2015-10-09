**Can you put "This class is fun" into bar.txt?**

    (master) David Jarrett
    NoNames-MacBook-Air:chapter_15 $ echo 'This class is fun!' >> bar.txt
    
    (master) David Jarrett
    NoNames-MacBook-Air:chapter_15 $ ls
    Readme.md bar.txt
    
    (master) David Jarrett
    NoNames-MacBook-Air:chapter_15 $ cat bar.txt
    This class is fun!




**Can you put "Oh so much fun" into foo.txt?**

    
    (master) David Jarrett
    NoNames-MacBook-Air:chapter_15 $ echo 'Oh so much fun' >> foo.txt
    
    (master) David Jarrett
    NoNames-MacBook-Air:chapter_15 $ cat foo.txt
    Oh so much fun
    
    
*>> is used to write the output of the command on the left of the symbol to the end of the file on the right.*

*> is similar to >>, but will replace the contents of existing files.*


*< sends the contents of the file on the right to the command on the left.*

| *passes the output of one command to another command as an argument.*


