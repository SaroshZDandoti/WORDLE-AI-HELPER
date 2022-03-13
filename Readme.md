This is a AI helper to suggest and perform operations to find the new word in the new Wordle Game.  
I used an Oxford Dictionary words Dataset and trimmed out all the 5 letter words from it and stored them in a list.  

Now here where it gets fun.
I initially tried to remake the entire game within python so i can visualize it in a better way, but in order to remake the entire game , i also already need to know my own wordle word.    
You can see some outputs in my code where the wordle box is being created.

Now inorder to use it in the actual NY TIMES game, you obcviously need to enter the inferences you get from your guessed words into my code.
Each word you enter, will have 3 formats of output.
🟩Green - Correct letter and Correct Position. ( Input the word and its position in my code)   
🟨 Yellow - Correct letter , wrong Position.    
🟧/⬛Grey/ Red - Wrong letter.   


Scroll below to use the current version.   
Run the first cell to load the dataset.
If you use this smartly you will always hit the answer in the 2nd and  3rd try.  

### How to Use?  
1. Put the yellow words in the contains list using quotations and commas.   
2. Put the green words in the fixed list and in the fixedpos list enter their positions. Note: the First letter position is 0, so 0 - 4.   
3. Put the greyed out letter (not present in the word letters) in the exclude list.

I generally use the word ARISE, MONTH or CRANE to eliminate most options.   
 ARISE because it has the 3 vowels and R and S too are common occuring letters.    
Check the analysis above to infer.    
I am working constantly on this code and will be  updated to play and suggest the entire word by itself.      
Till then Enjoy this piece of code below.  


# Happy Coding! 🙂
