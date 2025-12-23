# Ex02 Time Table
## Date: 21/11/2025
## Ref No: 25019212

## AIM
To write a html webpage page to display your slot timetable.

## ALGORITHM
### STEP 1
Create a Django-admin Interface.

### STEP 2
Create an App inside the Django project.

### STEP 2
Create a static folder uder the created App and insert HTML code.

### STEP 3
Create a simple table using ```<table>``` tag in html with the relevant attributes.

### STEP 4
Add rows using ```<tr>``` tag.

### STEP 5
Add your course schedule using ```<td>``` tag.

### STEP 6
Execute the program using runserver command.

## PROGRAM

```
<html>
    <body style="font-family: 'Times New Roman';">

        <!-- COLLEGE BANNER FROM PROVIDED URL -->
        <div style="text-align:center;">
            <img src="https://encrypted-tbn0.gstatic.com/images?q=tbn:ANd9GcQcaRJf5gDrxVN9XNsyCs-KV5ddOaQcbzT2yg&s"
                 alt="College Banner"
                 style="width:900px; height:130px; object-fit:contain;">
        </div>

        <br>

        
        <table border="1" cellspacing="2" cellpadding="2" align="center">
            <caption style="font-size:20px; font-weight:bold;">
                SLOT TIME TABLE - SAISRISH K S (25017319)
            </caption>

            <tr bgcolor="red">
                <th>Day/time</th>
                <th>Monday</th>
                <th>Tuesday</th>
                <th>Wednesday</th>
                <th>Thursday</th>
                <th>Friday</th>
                <th>Saturday</th>
            </tr>

            <tr>
                <td bgcolor="yellow">8-10</td>
                <td bgcolor="cyan">Public Speaking</td>
                <td bgcolor="cyan">Public Speaking</td>
                <td bgcolor="cyan">Web Application</td>
                <td bgcolor="cyan">Free Slot</td>
                <td bgcolor="cyan">Public Speaking</td>
                <td bgcolor="cyan">Free Slot</td>
            </tr>

            <tr>
                <td bgcolor="yellow">10-12</td>
                <td bgcolor="cyan">Free Slot</td>
                <td bgcolor="cyan">Web Application</td>
                <td bgcolor="cyan">Public Speaking</td>
                <td bgcolor="cyan">Free Slot</td>
                <td bgcolor="cyan">Free Slot</td>
                <td bgcolor="cyan">C Programming</td>
            </tr>

            <tr>
                <td bgcolor="yellow">12-1</td>
                <td bgcolor="cyan" colspan="6" align="center">LUNCH</td>
            </tr>

            <tr>
                <td bgcolor="yellow">1-3</td>
                <td bgcolor="cyan">C Programming</td>
                <td bgcolor="cyan">C Programming</td>
                <td bgcolor="cyan">Mentor Meet</td>
                <td bgcolor="cyan">Free Slot</td>
                <td bgcolor="cyan">Free Slot</td>
                <td bgcolor="cyan">Free Slot</td>
            </tr>

            <tr>
                <td bgcolor="yellow">3-5</td>
                <td bgcolor="cyan">Web Application</td>
                <td bgcolor="cyan">Web Application</td>
                <td bgcolor="cyan">Web Application</td>
                <td bgcolor="cyan">C Programming</td>
                <td bgcolor="cyan">Free Slot</td>
                <td bgcolor="cyan">C Programming</td>
            </tr>
        </table>

        <br><br>

        
        <table border="1" cellspacing="0" cellpadding="6"
               style="border-collapse: collapse; width: 700px; font-size: 18px;"
               align="center">

            <tr>
                <th>S.No</th>
                <th>Subject Code</th>
                <th>Subject Name</th>
            </tr>

            <tr>
                <td>1</td>
                <td>19AI304</td>
                <td>Fundamentals of C Programming</td>
            </tr>

            <tr>
                <td>2</td>
                <td>19AI414</td>
                <td>Fundamentals of Web Application Development</td>
            </tr>

            <tr>
                <td>3</td>
                <td>19EN105</td>
                <td>Public Speaking</td>
            </tr>

        </table>

    </body>
</html>
```


## OUTPUT
<img width="1459" height="791" alt="image" src="https://github.com/user-attachments/assets/05566110-89ee-4bc0-aa57-1b1ffc72f770" />



## RESULT
The program for creating slot timetable using basic HTML tags is executed successfully.
