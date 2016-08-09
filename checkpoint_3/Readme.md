
If you're not already, please go into the checkpoint_3 directory.

    (master) Neheniah Owens
    Nehemiahs-MacBook-Pro:learn-command-line-exercises $ cd checkpoint_3
    
Can you rename foo/bar/file1.txt to foo/blah.txt?

    (master) Neheniah Owens
    Nehemiahs-MacBook-Pro:checkpoint_3 $ mv foo/bar/file1.txt foo/blah.txt
    
Let's make a copy of foo/blah.txt and put it in the foo/bar/baz directory.

    (master) Neheniah Owens
    Nehemiahs-MacBook-Pro:checkpoint_3 $ cp foo/blah.txt foo/bar/baz

What happens if you touch an existing file. (Hint:  The answer is not nothing...)

    When using touch [file_name] it creates an updated timestamp. If there is no existing file a new one is created.
    (master) Neheniah Owens
    Nehemiahs-MacBook-Pro:checkpoint_3 $ touch foo/blah.txt

Can you copy the foo/blah.txt file to slash temp?

    (master) Neheniah Owens
    Nehemiahs-MacBook-Pro:checkpoint_3 $ cp -R foo/blah.txt /Users/User/temp

Can you copy .bash_profile in your home directory to the current directory? (Do not use cd here...)

    No
    (master) Neheniah Owens
    Nehemiahs-MacBook-Pro:checkpoint_3 $ cp -R .bash_profile Users/User/workspace/davinci_coders_t2_2016/homework/learn-command-line-exercises/checkpoint_3
    cp: .bash_profile: No such file or directory
    
What's in foo/blah.txt?

    (master) Neheniah Owens
    Nehemiahs-MacBook-Pro:checkpoint_3 $ cat foo/blah.txt
        
Can you show me what's in foo/blah.txt one page at a time?

    (master) Neheniah Owens
    Nehemiahs-MacBook-Pro:checkpoint_3 $ more foo/blah.txt
    
    By pressing the spacebar while the contents of the file are being displayed you can page through the entire file.