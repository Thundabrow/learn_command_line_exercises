What option to ls tells it to output file size in human readable form?

    man ls
      -h      When used with the -l option, use unit
                 suffixes: Byte, Kilobyte, Megabyte, Giga-
                 byte, Terabyte and Petabyte in order to
                 reduce the number of digits to three or
                 less using base 2 for sizes.

    Example:  nonames-air:chapter_19 $ ls -lh
              total 8
              -rw-r--r--  1 WhiteWolf  staff   1.3K Oct 10 23:31 Readme.m


Is there a case insensitive option to grep?

     man grep

    -i, --ignore-case
                 Perform case insensitive matching.  By
                 default, grep is case sensitive.


What does the -r and -f options to rm do exactly?

    man rm
         -f          Attempt to remove the files without
                     prompting for confirmation, regard-
                     less of the file's permissions.  If
                     the file does not exist, do not dis-
                     play a diagnostic message or modify
                     the exit status to reflect an error.
                     The -f option overrides any previous
                     -i options.
                     
         -r is equivalent to -R
         
         -R          Attempt to remove the file hierarchy
                          rooted in each file argument.


What does the ifconfig command do?

    man ifconfig
    ifconfig -- configure network interface parame-
         ters
