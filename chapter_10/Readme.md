ROBOCOPY is the Windows command-line command to copy files.

**Can you copy the foo.txt file to slash temp?  (Create foo.txt first...)**
    NoNames-MacBook-Air:chapter_10 $ touch foo.txt
    
    (master) David Jarrett
    NoNames-MacBook-Air:chapter_10 $ cp foo.txt /tmp
    
    (master) David Jarrett
    NoNames-MacBook-Air:chapter_10 $ ls /tmp
    KSOutOfProcessFetcher.501.HVXI9pQwBk_bgiVJaTNhiQNhqxc=
    foo.txt
    launch-EAqwWl
    launch-q55eNz
    launchd-151.TBpFcR
    launchd-258.ylmJtQ
    launchd-428.ioXCN0
    
    
**Can you copy .bash_profile in your home directory to the current directory?**

    NoNames-MacBook-Air:~ $ cp .bash_profile /Users/WhiteWolf/workspace/davinci_coders_t3_2015/in_class/homework/learn_command_line_exercises/chapter_10
    
    
    NoNames-MacBook-Air:~ $ cd /Users/WhiteWolf/workspace/davinci_coders_t3_2015/in_class/homework/learn_command_line_exercises/chapter_10
    
    (master) David Jarrett
    NoNames-MacBook-Air:chapter_10 $ ls
    Readme.md foo.txt   tmp
    
    (master) David Jarrett
    NoNames-MacBook-Air:chapter_10 $ ls -a
    .             .bash_profile foo.txt
    ..            Readme.md     tmp
    
    
cp -r tmp newdir/   # copies contents of tmp to newdir

cp foo.txt ~
  


