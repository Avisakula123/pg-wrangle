# pg-wrangle
shell-data-processing assignment challenge

## Assigned play
- Tragedy - number 8 
- Romeo and Juliet

## Speakers I have choosen 
- GOBBO
- NERISSA

## The question is who speaks more
- The commands used are 
 curl "http://shakespeare.mit.edu/merchant/full.html" -O "data.txt"
- sed command used to remove angular brackets in entire data file.
- curl "http://shakespeare.mit.edu/merchant/full.html" | sed 's/<\/*[^>]*>//g' > A.txt
- $ grep 'GOBBO' 'A.txt' -c
- $ grep 'NERISSA' 'A.txt' -c
- $ grep 'GOBBO' 'A.txt' -c > "gobbo-output.txt"
- $ grep 'NERISSA' 'A.txt' -c > "nerissa-output.txt"

- 'GOBBO' speaks 20 times and 'NERISSA' speaks 46 times.


