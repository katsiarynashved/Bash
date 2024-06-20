# Bash
My stydy included working with bash. Here are the task I made and some more.

### Task "University"
In this task directory "universiry" has to be created and file "students.txt" should be added. Then I needed to add the data in that file using editor in bash and create some more files in directory "university". After that several requests have to be done to find nesessary information. 
Below is the table with the requests I sent and responses I got.
<br>
<br>

| Number  | Request | Response |
| --- | ------------- | ------------------------------------ | 
| 1  | kate@LAPTOP-VSNQSSAB:~/Kate$ ls  | Danya  Lucky  dir2  dir3  new_file.txt  text_file.txt  |
| 2  | kate@LAPTOP-VSNQSSAB:~/Kate$ mkdir university  |   |
| 3  | kate@LAPTOP-VSNQSSAB:~/Kate$ ls  | Danya  Lucky  dir2  dir3  new_file.txt  text_file.txt  university  |
| 4  | kate@LAPTOP-VSNQSSAB:~/Kate$ cd university  |   |
| 5  | kate@LAPTOP-VSNQSSAB:~/Kate/university$ touch students.txt  |   |
| 6  | kate@LAPTOP-VSNQSSAB:~/Kate/university$ nano students.txt  |   |
| 7  | kate@LAPTOP-VSNQSSAB:~/Kate/university$ cat students.txt  | Aleksandra Ivanova Smirnova <br>Mihail Egorovich Petrov <br>MIHAIL Alekseevich Sokolov <br>Maria Sergeevna SMirnova <br>maria Urevna Rozkova|
| 8  | kate@LAPTOP-VSNQSSAB:~/Kate/university$ touch faculties.txt faculties.png students.png  |   |
| 9  | kate@LAPTOP-VSNQSSAB:~/Kate/university$ ls  | faculties.png  faculties.txt  students.png  students.txt  |
| 10  | kate@LAPTOP-VSNQSSAB:~/Kate/university$ grep Maria students.txt  | Maria Sergeevna SMirnova  |
| 11  | kate@LAPTOP-VSNQSSAB:~/Kate/university$ grep -i maria students.txt  | Maria Sergeevna SMirnova <br>maria Urevna Rozkova  |
| 12  | kate@LAPTOP-VSNQSSAB:~/Kate/university$ grep -iv maria students.txt  | Aleksandra Ivanova Smirnova <br>Mihail Egorovich Petrov <br>MIHAIL Alekseevich Sokolov  |
| 13  | kate@LAPTOP-VSNQSSAB:~/Kate/university$ grep -c Smirnova students.txt  | 1  |
| 14  | kate@LAPTOP-VSNQSSAB:~/Kate/university$ grep -icv Smirnova students.txt  | 3  |
| 15  | kate@LAPTOP-VSNQSSAB:~/Kate/university$ find . -name "٭.txt"  | ./students.txt <br>./faculties.txt  |
| 16  | kate@LAPTOP-VSNQSSAB:~/Kate/university$  find . -name "students.*"  | ./students.png <br>./students.txt  |
| 17  | kate@LAPTOP-VSNQSSAB:~/Kate/university$ find . -name faculties.txt  | faculties.txt  |
