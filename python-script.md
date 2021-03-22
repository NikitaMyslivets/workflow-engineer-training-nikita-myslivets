### Write a Python Script
Write a python script that takes a folder as an input and outputs the 5 most frequent file formats in descending order.

The script should take a folder as an argument.

The script should provide output as in the example below.<br>
The output should start with the line `Top 5 file formats in $folder_name folder: `, each file format should be on the new line, the number of occurrences should be next to file format. Each line should be formatted as in the example below.

If several file formats have the same number of occurrences in the folder, output them in the arbitrary order.

The script must parse all folders in the root folder using **recursion**.

Name your script `folders_script.py`

**Example**

Here is the content of new_folder
```
new_folder
    test.txt
    secret_files
        file1.docx
        file2.txt
        file3.png
        ExamSolutions.java
        ExamTest.java
        file4.xml
        homeworks
            homeworks_description.txt
            homework_git.md
            homework_grades.xlsx
    essay.docx
    essay_draft.docx
    essay.pdf
    hello_world.py
    test_hello.py
    new.txt
    project
        README.md
        Main.java
        Test.java
        Main.class
        src
            HelloWorld.java
```
Here is the example of the script running:

`> python folders_script.py new_folder` <br>
`Top 5 file formats in new_folder folder: ` <br>
`.java   5`<br>
`.txt    4`<br>
`.docx   3`<br>
`.md     2`<br>
`.py     2`<br>


To test your solution fill in the test_data folder with arbitrary empty files. We should be able to run your script using your test data.<br>
Provide us with the example of successfully run script using your test_data folder.
