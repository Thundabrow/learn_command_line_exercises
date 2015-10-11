**Show me the lines in foo.txt that have "ERROR" in them.**

    grep "ERROR" foo.txt



**Show me the lines in bar.txt that have "davinci" in them.**

    grep "davinci" bar.txt



**Can you print all the lines in text files that have your first and last name in them?**

    grep *.txt "David" -i
    grep *.txt "Jarrett" -i
    grep *.txt "David Jarrett" -i
    
    
# The -i option ignores case, i.e., it will find uppercase and lowercase text that matches the search terms.


