# Linux basic command -

1. pwd : This command is used to find that which current directory you are now. 
// Output -> /c/Users/dIZZY wORLD/Desktop

2. clear : This command is used to clear all stuff that you are showing om linux terminal
// Output -> 

3. ls : this command will show you how many files of list are exists in your current folder
// Output -> your all files will be appeared here.

4. ls -a :  This command will show you more hidden files in your folder
// Output -> All hidden files 

5. ls -lh : This command will show you about the more detail of your existing folder like size and other .
// Output -> all size and detail will show this command

6. cd <directory_name> : With the help of this command you can directly switch your directory if you wanted to perform on particular tasks. after putting this cd command you can check this through your current directory by using pwd command . 
// Output -> your directory get switched

7. cd .. : By using this command you will jump on folder back . you can also use this command multiple times.
// Input --> pwd run -> /c/Users/dIZZY wORLD/Desktop
// Output --> cd .. run -> /c/Users/dIZZY wORLD

8. mkdir <new_folder_name> : By this command you can create a new folder in your system .
// Run -> mkdir Sourabh 
// Output - new folder will be created in your existing directory

9. rmdir <new_folder_name> : By using this command you can remove your folder from existing file
// run -> rmdir new_folder_name
// Output ->  folder will remove and you will be shifted into the back folder if you was in a that time .

10. touch <new.txt> : you can create new file by using this command 
//  run -> touch new.txt
// Output -> new file will be created "new.txt"

11. rm <new.txt> : This command will helps you to remove this created file
// run -> rm new.txt
// Output -> files will be deleted 

12. rm -rf <new_folder> : this command will be deleted the file inside the folder and also will deleted the file . let us understand with some examples -:
// Example -:
// mkdir new_folder /* folder is created */
// cd new_folder     /* let's move to the directory */
// touch n1.txt      /* create a new file inside the new folder*/
// rm new_folder     /* output -> you can not remove new_folder in directory */
// rmdir new_folder  /* output -> failed to remove new_folder : directory is not empty */
 # Note : you can see there we are not able to delete non empty folder with this command
// run -> rm -rf new_folder  
// Output -> now by using this command you can be deleted non empty files also

13. vim <new_file> : this command is used to open the file. By using this command my n1.txt file will be open. By this command you can edit your file also after opening new file you have to press "i" to insert the data. once you insert the data you have to press escape button and press :wq for the save your file.
run -> vim <n1.txt>
output -> this n1 file will be open in your browser
 
14. cat <your_file> : if you wanted to print content of your file then hit this command
run -> cat n1.txt
output -> sourabh sharma 
and hello i am coder 
you dont know who i am 
i am elvish yadav fan 
systemmm

# note : if you dont wanted to make changes with your file then simply escape and run this-> :q!
Output -> there will no external chnages with your file

#note : if you wanted to delete your single lines then simply press two times " d "

15. open <new_file> : by this command you can open your file through linux

16. man ls : this command will print the documentation on pressing enter

17.  find <folder_name> -name "<*.last_extension>" : this will helps you to search files
run ->  find Linux -name "*.txt"
output -> Linux/n1.txt

18. cp <existing_file> <rename_newfile> : by using this you can create copy of your existing file
// example -> ls -> Sourabh/  n1.txt
// run -> $ cp n1.txt m1.txt
// output -> Sourabh/  m1.txt  n1.txt

19. mv <existing_file> <new_file> : you can direcly move your existing file to another existing file or newly created file
//ls -> ls -> Sourabh/  n1.txt
// run -> mv n1.txt Sourabh
// Output -> n1.txt file will be found in the Sourabh folder

20. mv <existing_file> <rename_file> : you can also rename file with this command
// run -> mv p1.txt rename.txt
//output -> file name is renamed from p1.txt to rename.txt

21. ls | grep <File_contain_words> : you can search the existing file name through this command
// run -> ls | grep java
// output -> Array.java
Bits.java
Complexity.java
Dsa.java
DsaTest.java
Functions.java
Loops.java
Mycode.java
Newproblems.java
Oops.java
Recursion.java
Recursion2.java
Sortings.java
Strings.java

22. echo "this command is like print statement in programming" -> this will print your text as well as what you mentioned in the quotes
// run -> echo "Hello WOrld"
// output -> Hello WOrld

23. ls > <file_you_wanted_to_seen> : this data of the all terminal will be showing in this file
run -> ls > file.txt
output -> last terminal data will show here




