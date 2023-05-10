## grep -c
```
$ grep -c "and" ./technical/911report/chapter-5.txt  
383
```
```
$ grep -c "lymph" ./technical/biomed/1471-2172-3-9.txt  
22
```
The `-c` option for `grep` gives a count of lines with the given string in it. This option can be useful for when you just want the number of lines with the given string without needing to create another file to use `wc` on.  
Found on:  [https://man7.org/linux/man-pages/man1/grep.1.html](https://man7.org/linux/man-pages/man1/grep.1.html).  
  
## grep -i
```
$ grep -i "no" ./technical/government/Media/A_helping_hand.txt  
knowing she wanted to represent the poor. She graduated in 1995
... There was no way I could make that payment. I barely make it
now with my regular bills."
December 1999. The nonprofit operation pays the debts of attorneys 
keep lawyers around after they got a few years of experience. Not  
"It really had become an economic impossibility to take these      
When she stepped down, she had time to notice what was happening   
said. "It had gone from being an economic sacrifice as it was in
canals and rat bite fever, a nonfatal malady that particularly     
affects children. Mintie noticed that health-care professionals    
Her work was noticed by Oprah Winfrey, who invited her on the TV   
Award" from Oprah's Angel Network, a nonprofit organization that   
money has gone to her recipients -- none was spent on overhead.
Fourteen people now receive money from Uncommon Good. Debt
```
```
$ grep -i "doc" ./technical/plos/journal.pbio.0020063.txt
        biotechnology and pharmaceutical companies that develop drugs and medical devices; doctors,
        lived up to their full potential to save lives and improve 
their quality. Doctors,
        make it easy for people to read outside their specialty area. “Doctors are systems
```
The `-i` option for `grep` allows for the search of lines in a file that contain a string reguardless of the strings case type. This option could be useful for when you want to read all lines that contain a string and also do not care if the string found is upper case or lower case.  
Found on:  [https://man7.org/linux/man-pages/man1/grep.1.html](https://man7.org/linux/man-pages/man1/grep.1.html).  
  
## grep -w
```
$ grep -w "present" ./technical/911report/chapter-12.txt
                present fiscal year 2004, total federal spending on defense (including expenditures
                tolerance among people of different faiths can and must prevail. The present
                capita income has dropped from $28,000 at its height to the present level of about
                through regulated channels, present themselves to border security officials, or
            What information is an individual required to present and in what form?
                present system is disrupting travel to the United States. Overall, visa applications
                    present aviation security challenges.
```
```
$ grep -w "gene" ./technical/biomed/1471-213X-2-7.txt
        developing arista using a Fz-GFP encoding transgene gene.
          time of action of the gene.
```
The `-w` option for `grep` allows for the search of a specific word rather than a string. This option could be useful for searching for lines with a specific word that is common in other words.  
Found on:  [https://man7.org/linux/man-pages/man1/grep.1.html](https://man7.org/linux/man-pages/man1/grep.1.html).  
  
## grep -n
```
$ grep -n "article" ./technical/plos/journal.pbio.0020164.txt
104:        issue in the recent literature. A good example can be found in an article by Nicholas   
108:        Both articles deal with a classical problem in developmental biology, namely, how       
135:        Indeed, the major message of the von Dassow article was that the authors had uncovered a
```
```
$ grep -n "change" ./technical/biomed/1471-2229-2-11.txt
243:          also changed from a cosuppressing state in the T2
517:        epigenetic change. Here, combining a master locus (C73)
```
The `-n` option for `grep` gives the line numbers along with the lines that contain the given string. This option could be useful if you need to see more that just one line around the given string, so you can find where exactly the line is within the file.
Found on:  [https://man7.org/linux/man-pages/man1/grep.1.html](https://man7.org/linux/man-pages/man1/grep.1.html).
