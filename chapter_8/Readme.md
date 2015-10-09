pushd stores your current directory on a stack and takes you to the directory that you list in the command argument.

popd takes you back to the top directory on the stack created by pushd.



    (master) David Jarrett
    NoNames-MacBook-Air:john $ pushd /tmp
    /tmp ~/workspace/davinci_coders_t3_2015/in_class/homework/learn_command_line_exercises/chapter_8/tmp/stuff/things/frank/joe/alex/john
    
    
    NoNames-MacBook-Air:tmp $ popd
    ~/workspace/davinci_coders_t3_2015/in_class/homework/learn_command_line_exercises/chapter_8/tmp/stuff/things/frank/joe/alex/john
    
    (master) David Jarrett
    NoNames-MacBook-Air:john $ pushd ~/workspace
    ~/workspace ~/workspace/davinci_coders_t3_2015/in_class/homework/learn_command_line_exercises/chapter_8/tmp/stuff/things/frank/joe/alex/john
    
    
    NoNames-MacBook-Air:workspace $ popd
    ~/workspace/davinci_coders_t3_2015/in_class/homework/learn_command_line_exercises/chapter_8/tmp/stuff/things/frank/joe/alex/john
    
    (master) David Jarrett
    NoNames-MacBook-Air:john $ pushd ..
    ~/workspace/davinci_coders_t3_2015/in_class/homework/learn_command_line_exercises/chapter_8/tmp/stuff/things/frank/joe/alex ~/workspace/davinci_coders_t3_2015/in_class/homework/learn_command_line_exercises/chapter_8/tmp/stuff/things/frank/joe/alex/john
    
    (master) David Jarrett
    NoNames-MacBook-Air:alex $ popd
    ~/workspace/davinci_coders_t3_2015/in_class/homework/learn_command_line_exercises/chapter_8/tmp/stuff/things/frank/joe/alex/john
    
    (master) David Jarrett
    NoNames-MacBook-Air:john $ pushd ~
    ~ ~/workspace/davinci_coders_t3_2015/in_class/homework/learn_command_line_exercises/chapter_8/tmp/stuff/things/frank/joe/alex/john
    
    
    NoNames-MacBook-Air:~ $ popd
    ~/workspace/davinci_coders_t3_2015/in_class/homework/learn_command_line_exercises/chapter_8/tmp/stuff/things/frank/joe/alex/john
