
# Chapter 16: Wildcard Matching

## Do More

### Clean up everything in temp from all the exercises so far

    Nehemiahs-MacBook-Pro:temp $ ls
    23                    apples                ex13.2.txt            i_am_cool             stuff
    Desktop               blah.txt              ex13.txt              mystuff               things
    Nehemiahs-Macbook-Pro ex12.txt              i                     something             today

    Nehemiahs-MacBook-Pro:temp $ rmdir things/
    
    
    Nehemiahs-MacBook-Pro:temp $ rm -rf apples/
    
    
    Nehemiahs-MacBook-Pro:temp $ rm -rf i_am_cool/
    
    
    Nehemiahs-MacBook-Pro:temp $ rm -rf mystuff/
    
    
    Nehemiahs-MacBook-Pro:temp $ rm -rf stuff/
    
    
    Nehemiahs-MacBook-Pro:temp $ rm -rf 23/
    
    
    Nehemiahs-MacBook-Pro:temp $ rm -rf i/
    
    
    Nehemiahs-MacBook-Pro:temp $ rm ex13.txt
    
    
    Nehemiahs-MacBook-Pro:temp $ rm ex13.2.txt
    
    
    Nehemiahs-MacBook-Pro:temp $ rm ex12.txt
    
    
    Nehemiahs-MacBook-Pro:temp $ rm blah.txt
    
    
    Nehemiahs-MacBook-Pro:temp $ ls
    Desktop               Nehemiahs-Macbook-Pro today
    
    
    Nehemiahs-MacBook-Pro:temp $ rm -rf today/
    
    
    Nehemiahs-MacBook-Pro:temp $ ls
    Desktop               Nehemiahs-Macbook-Pro  
      
### Write in your notebook to be careful when running recursive remove on files

    When using rm -rf you can easily delete every file and directory on your computer if not typed in the correct format.
