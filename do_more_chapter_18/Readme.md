
# Chapter 18: Looking inside files (grep)

## Do More

### Use quotes to find "new file" and "old file" and "This is".

    Nehemiahs-MacBook-Pro:temp $ grep "new file" *.txt
    newfile.txt:This is a new file
    newfile.txt:This is a new file
    newfile.txt:This is a new file.
    
    Nehemiahs-MacBook-Pro:temp $ grep "old file" *.txt
    oldfile.txt:This is a old file.
    oldfile.txt:This is a old file.
    oldfile.txt:This is a old file.
    
    
    Nehemiahs-MacBook-Pro:temp $ grep "This is" *.txt
    newfile.txt:This is a new file
    newfile.txt:This is a new file
    newfile.txt:This is a new file.
    oldfile.txt:This is a old file.
    oldfile.txt:This is a old file.
    oldfile.txt:This is a old file.
    
### Take the list of videos you created (or any other list) and use it to find some videos you want to find.

I have no .mp4 videos on my hard drive available for viewing.

### Unix: You can use -i to ignore case with grep. Try grep -i new *.txt

I have no .mp4 videos on my hard drive available for viewing but used the previous list for the do_more purpose

    Nehemiahs-MacBook-Pro:temp $ grep -i "old file" *.txt
    oldfile.txt:This is a old file.
    oldfile.txt:This is a old file.
    oldfile.txt:This is a old file.