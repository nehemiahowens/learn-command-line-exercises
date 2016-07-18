
# Chapter 10: Copy a file (cp)

## Do More
> ***NOTE***: The answers for this chapter should not include the use of cd (change directory).

### Use the cp -r command to copy more directories with files in them.
    
    Nehemiahs-MacBook-Pro:temp $ cp -r newplace today
    Nehemiahs-MacBook-Pro:temp $ ls today/
             iamcool.txt newplace
    Nehemiahs-MacBook-Pro:temp $ ls something/
    awesome.txt
    Nehemiahs-MacBook-Pro:temp $ cp -r something today
    Nehemiahs-MacBook-Pro:temp $ ls today/
    iamcool.txt newplace    something
    
### Copy a file to your home directory or desktop.

    Nehemiahs-MacBook-Pro:temp $ cp -R newplace /Users/User/mystuff
    
### Find these files in your graphical user interface and open them in a text editor.

    Finder/User/mystuff/newplace/awesome.txt
    
### Notice how sometimes I put a / (slash) at the end of a directory? That makes sure the file is really a directory, so if the directory doesn't exist I'll get an error.

    Nehemiahs-MacBook-Pro:temp $ ls today/
    iamcool.txt newplace
        
    Nehemiahs-MacBook-Pro:temp $ cp -r somthing today
    cp: somthing: No such file or directory    
