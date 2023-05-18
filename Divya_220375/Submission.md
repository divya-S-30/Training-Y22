LEVEL 1 to LEVEL 2-  cat ./-  (To handle dashed(-) file use./)
                     Password-rRGizSaX8Mk1RTb1CNQoXTcYZWU6lgzi
                     
LEVEL 2 TO LEVEL 3- cat "spaces in this filename"  (for long file names and files having spaces use double quotted commas)
                     Password-aBZ0W5EmUfAf7kHTQeOwd8bauFJ2lAiG
                     
LEVEL 3 to LEVEL 4-cd inhere (go to inhere directory)
                   ls -a   (list all hidden files)
                   Password-2EW7BBsr6aMMoJ2HjW067dm8EgX26xNe
                   
LEVEL 4 to LEVEL 5-cd inhere 
                   ls -la (list all the files in inhere directory)
                   file ./*  (for seeing the datatype so we can find which is human readable)
                   cat ./-file7
                   Password-lrIWWI6bB37kxfiCQZqUdOIYfr6eEeqR
                   
LEVEL 5 to LEVEL 6-find inhere -type f -size 1033c (find a file in inhere directory of 1033 bytes)
                   Password-P4L4vucdmLnm8I7Vl7jG1ApGSfjYKqJU
                   
LEVEL 6 to LEVEL 7-find / -type f -user bandit7 -group bandit6 -size 33c  (find a file owned by a user and a group of a specific size)
                   (Open the file having not permission denied)
                   Password-z7WtoNQU2XfjmMtWA8u5rN4vzqu4v99S
                   
LEVEL 7 to LEVEL 8- grep --fixed-strings "millionth" data.txt  (search for an exact string)
                    Password-TESKZC0XvTetK0S9xNwm25STk5iWrBvP
                    
LEVEL 8 to LEVEL 9-  sort data.txt | uniq -u (sort the line that comes once)
                     Password-EN632PlfYiZbn3PhVK3XOGSlNInNE00t
                     
LEVEL 9 to LEVEL 10- cat data.txt
                     strings data.txt   ( it print all strings)
                     Password-G7w8LIi6J3kTb8A7j9LgrywtEUlyyp6s
                     
LEVEL 10 to LEVEL 11-base64 --decode data.txt   (Decode the base64 content)
                     Password-6zPeziLdR2RKNdNYFNb6nVCKzphlXHBM
                     
LEVEL 11 to LEVEL 12-cat data.txt
                      tr 'A-Za-z' 'N-ZA-Mn-za-m' <<< WIAOOSFzMjXXBC0KoSKBbJ8puQm5lIEi     (Rotate the letters by 13 positions)
                      Password-JVNBBFSmZwKKOP0XbFXOoW8chDz5yVRv
