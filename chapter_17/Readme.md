**Can you show me all the files in slash temp slash foo?**

    NoNames-MacBook-Air:learn_command_line_exercises $ find /tmp/foo "*.*" -print
    /tmp/foo
    /tmp/foo/file1.txt
    /tmp/foo/file2.txt
    /tmp/foo/file3.txt
    find: *.*: No such file or directory



**What log files are in your log directory?**

    (master) David Jarrett
    NoNames-MacBook-Air:chapter_17 $ find ./tmp/foo "*.log" -print
    ./tmp/foo
    ./tmp/foo/log1.log
    ./tmp/foo/log2.log
    ./tmp/foo/log3.log
    find: *.log: No such file or directory
