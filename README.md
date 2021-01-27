# srg-wrangle
## Assigned play: (5) Loves Labours Lost

## Speaker 1: BIRON
## Speaker 2: LONGAVILLE
## Question: Who speak more in the play ?
Ans: In the above play BIRON speak 167 times where LONGAVILLE speak only 48 times. So BIRON speak more in the play.
## Commands used:
-  curl "http://shakespeare.mit.edu/lll/full.html" | sed 's/<\/*[^>]*>//g' > srginput.txt (used curl command To take the input fron the http link). 
-  grep -o "BIRON" srginput.txt -c > output.txt
-  grep -o "LONGAVILLE" srginput.txt -c >> output.txt
- Whrere -0 show only the part of a line matching PATTERN
- cat output.txt command to view the file

