# LInux-assignment

                                                      Linux assignment

Task 1: Creating and Renaming Files/Directories
Command 1: mkdir test_dir
Explanation: mkdir command se naya directory banate hain. Yahan test_dir naam ka folder create hua. 
Command 2: cd test_dir
touch example.txt
Explanation: cd se directory mein jaate hain. touch command se empty file create hoti hai. 
Command 3: mv example.txt renamed_example.txt
ls
Explanation: mv command file rename karne ke liye use hoti hai. ls se verify kiya ki file rename hui. 

Task 2: Viewing File Contents 
Command 1: cat /etc/passwd
Explanation: cat command file ka poora content terminal mein dikhata hai. 










Command 2: head -5 /etc/passwd
Explanation: head -5 command file ki sirf pehli 5 lines dikhata hai. 





Command 3: tail -5 /etc/passwd
Explanation: tail -5 command file ki sirf aakhri 5 lines dikhata hai. 















Task 3: Searching for Patterns
Command: grep "root" /etc/passwd
Explanation: grep command file mein specific word dhundta hai. Yahan /etc/passwd mein "root" word wali saari lines show hui. 














Task 4: Zipping and Unzipping
Command 1: zip -r test_dir.zip test_dir


Explanation: zip -r command se directory ko compress karke .zip file banate hain. 

Command 2: unzip test_dir.zip -d unzipped_dir
ls
Explanation: unzip command se zip file ko naye folder mein extract karte hain. ls se verify kiya. 









Task 5: Downloading Files
Command: wget https://www.gnu.org/licenses/gpl.txt
Explanation: wget command internet se file download karne ke liye use hoti hai. URL dete hain aur file automatically download ho jaati hai. 










Task 6: Changing Permissions
Command:touch secure.txt
chmod 444 secure.txt
ls -l secure.txt
Explanation: chmod 444 command file ko read-only banata hai sabke liye — owner, group, aur others. ls -l se -r--r--r-- permission verify hoti hai. 








Task 7: Working with Environment Variables
Command : export MY_VAR="Hello, Linux!"
echo $MY_VAR
Explanation: export command se environment variable set karte hain. echo se variable ki value print hoti hai. Output mein Hello, Linux! aaya. 






