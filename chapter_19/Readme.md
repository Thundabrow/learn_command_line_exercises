What option to ls tells it to output file size in human readable form?

    man ls
    -s      Display the number of file system blocks
                 actually used by each file, in units of
                 512 bytes, where partial units are
                 rounded up to the next integer value.  If
                 the output is to a terminal, a total sum
                 for all the file sizes is output on a
                 line before the listing.  The environment
                 variable BLOCKSIZE overrides the unit
                 size of 512 bytes.


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
