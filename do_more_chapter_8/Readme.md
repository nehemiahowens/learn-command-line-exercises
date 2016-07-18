
# Chapter 8: Moving around (pushd, popd)

## Do More

### Use these commands to move around directories all over your computer.

    Please use markdown formatting listing the command(s) you ran to accomplish this
    
### Remove the i/like/icecream directories and make your own, then move around in them.

    Nehemiahs-MacBook-Pro:temp $ rmdir i/like/icecream
    
    Nehemiahs-MacBook-Pro:temp $ mkdir -p 23/is/life
    
    
    Nehemiahs-MacBook-Pro:temp $ pushd 23/is/life/
    ~/temp/23/is/life ~/temp ~/temp
    
    
    Nehemiahs-MacBook-Pro:life $ popd
    ~/temp ~/temp
    
    
    Nehemiahs-MacBook-Pro:temp $ pwd
    /Users/User/temp
    
    Nehemiahs-MacBook-Pro:temp $ pushd 23/is
    ~/temp/23/is ~/temp ~/temp
    
    
    Nehemiahs-MacBook-Pro:is $ pwd
    /Users/User/temp/23/is
    
    
    Nehemiahs-MacBook-Pro:is $ popd
    ~/temp ~/temp
    
    
    Nehemiahs-MacBook-Pro:temp $ pwd
    /Users/User/temp

### Explain to yourself the output that pushd and popd print out to you. Notice how it works like a stack?

> The ```Pushd``` command allows for you to go into a different directory while saving the work in the current directory. 
> The ```Popd``` command allows you to access the last directory you ```pushd``` from.  

### You already know this, but remember that mkdir -p will make an entire path even if all the directories don't exist. That's what I did very first for this exercise.

> Using the ```mkdir -p``` command allows for multiple directories to be created without having to individually create each one; while at the same time printing the entire directory that can be utilized when needed.     
