
# Chapter 7: Remove Directory (rmdir)

## Do More

### Make 20 more directories and remove them all.

```Nehemiahs-MacBook-Pro:janet $ pwd
   /Users/User/temp/stuff/things/places/people/mark/john/jacob/jonah/jessica/janet```
> I am unable to remove the entire 20 directories as they are not all empty; rather they need to be removed individually as done below.

### Make a single path of directories that is 10 deep and remove them one at a time just like I did above.

    Nehemiahs-MacBook-Pro:mike $ rmdir michelle
    
    
    Nehemiahs-MacBook-Pro:mike $ cd ..
    
    
    Nehemiahs-MacBook-Pro:josiah $ rmdir mike
    
    
    Nehemiahs-MacBook-Pro:josiah $ cd ..
    
    
    Nehemiahs-MacBook-Pro:jackson $ rmdir josiah/
    
    
    Nehemiahs-MacBook-Pro:jackson $ cd ..
    
    
    Nehemiahs-MacBook-Pro:julie $ rmdir jackson/
    
    
    Nehemiahs-MacBook-Pro:julie $ cd ..
    
    
    Nehemiahs-MacBook-Pro:jerry $ rmdir julie/
    
    
    Nehemiahs-MacBook-Pro:jerry $ cd ..
    
    
    Nehemiahs-MacBook-Pro:jack $ rmdir jerry/
    
    
    Nehemiahs-MacBook-Pro:jack $ cd ..
    
    
    Nehemiahs-MacBook-Pro:james $ rmdir jack
    
    
    Nehemiahs-MacBook-Pro:james $ cd ..
    
    
    Nehemiahs-MacBook-Pro:janet $ rmdir james
    
    
    Nehemiahs-MacBook-Pro:janet $ cd ..
    
    
    Nehemiahs-MacBook-Pro:jessica $ rmdir janet/
    
    
    Nehemiahs-MacBook-Pro:jessica $ cd ..
    
    Nehemiahs-MacBook-Pro:jonah $ rmdir jessica/

### If you try to remove a directory with contents you will get an error. I'll show you how to remove these in later exercises.

```Nehemiahs-MacBook-Pro:~ $ rmdir temp/stuff/things/places/people/mark/john/jacob/jonah/jessica/janet
   rmdir: temp/stuff/things/places/people/mark/john/jacob/jonah/jessica/janet: Directory not empty```
        
