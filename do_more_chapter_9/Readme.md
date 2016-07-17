
# Chapter 9: Making Empty Files (Touch)

## Do More

### Make a directory, change to it, and then make a file in it. Then change one level up and run the rmdir command in this directory. You should get an error. Try to understand why you got this error.

    cd temp/
    touch iamcool.txt
    ls
    iamcool.txt  
      
    mkdir i_am_cool
    cd i_am_cool
    touch iamcool.txt
    ls
    iamcool.txt
    
    rmdir i_am_cool
    rmdir: i_am_cool/: Directory not empty

> I received the error Directory not empty from the iamcool.txt file that was created which would need to be removed before being able to remove the i_am_cool directory.