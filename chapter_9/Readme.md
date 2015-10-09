**Can you touch blah.txt?
Let's create foo.txt.**

    (master) David Jarrett
    NoNames-MacBook-Air:chapter_9 $ touch foo.txt
    
    (master) David Jarrett
    NoNames-MacBook-Air:chapter_9 $ touch blah.txt
    
    (master) David Jarrett
    NoNames-MacBook-Air:chapter_9 $ ls
    Readme.md blah.txt  foo.txt
    
    (master) David Jarrett
    NoNames-MacBook-Air:chapter_9 $ mkdir tmp
    
    (master) David Jarrett
    NoNames-MacBook-Air:chapter_9 $ cd tmp
    
    (master) David Jarrett
    NoNames-MacBook-Air:tmp $ touch file.txt
    
    (master) David Jarrett
    NoNames-MacBook-Air:tmp $ cd ..
    
    (master) David Jarrett
    NoNames-MacBook-Air:chapter_9 $ rmdir tmp
    rmdir: tmp: Directory not empty
    
*The above occurs because rmdir will not normally remove folders that contain files.

*Touching an existing file updates the timestamp on the file.
