**Can you rename foo.txt to blah.txt?**

    NoNames-MacBook-Air:chapter_11 $ mv foo.txt blah.txt
    
**Can you move the production.log file in the log directory to slash temp?**

    mv production.log /tmp


**Move a file in the newplace directory to another directory then move it back.**

    (master) David Jarrett
    NoNames-MacBook-Air:chapter_11 $ cd newplace
    
    (master) David Jarrett
    NoNames-MacBook-Air:newplace $ ls
    blarg.txt
    
    (master) David Jarrett
    NoNames-MacBook-Air:newplace $ mv blarg.txt log/
    mv: rename blarg.txt to log/: No such file or directory
    
    (master) David Jarrett
    NoNames-MacBook-Air:newplace $ mv blarg.txt ../log
    
    (master) David Jarrett
    NoNames-MacBook-Air:newplace $ cd ..
    
    (master) David Jarrett
    NoNames-MacBook-Air:chapter_11 $ cd log
    
    (master) David Jarrett
    NoNames-MacBook-Air:log $ ls
    blarg.txt
    
    (master) David Jarrett
    NoNames-MacBook-Air:log $ mv blarg.txt ../newplace
    
    (master) David Jarrett
    NoNames-MacBook-Air:log $ cd ../newplace
    
    (master) David Jarrett
    NoNames-MacBook-Air:newplace $ ls
    blarg.txt
