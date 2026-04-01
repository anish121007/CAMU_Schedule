# Ex08 CAMU Schedule using Bootstrap
## Date:31/03/26

## AIM:
To design a responsive and visually appealing CAMU Schedule using Bootstrap.

## DESIGN STEPS:

### Step 1:
Clone the repository from GitHub.

### Step 2:
Create Django Admin project.

### Step 3:
Create a New App under the Django Admin project.

### Step 4:
Add the Bootstrap CDN link inside the ```<head>``` section.

### Step 5:
Insert a table element with Bootstrap table classes.

### Step 6:
Construct the complete table.

### Step 7:
Add a header/footer displaying copyright information.

### Step 8:
Publish the website in the LocalHost.

## PROGRAM :
```
<!DOCTYPE html>
<html>
<head>
<title>Slot Timetable</title>
<link rel="stylesheet" href="https://maxcdn.bootstrapcdn.com/bootstrap/3.4.1/css/bootstrap.min.css">
<style>
header {
    text-align: center;
    padding: 10px;
    font-size: 24px;
    font-weight: bold;
    background: rgb(0, 0, 0);
    color: rgb(104, 103, 103);
    position: fixed;
    top: 0;
    width: 100%;
}
body {
    text-align: center;
    margin-top: 50px;
}
table {
    margin: auto;
}
footer {
    background: rgb(0, 0, 0);
    color: rgb(159, 159, 159);
    text-align: center;
    padding: 10px;
    position: fixed;
    bottom: 0;
    width: 100%;
}
</style>
</head>
<body>
<header>SLOT TIME TABLE</header>
<img src="logo.png" height="100" width="540">
<h3>ANISH K B(25019112)</h3>
<table class="table table-bordered">
<caption><b>Time Table</b></caption>
<tr class="bg-danger">
<th>Day/Time</th>
<th>Mon</th>
<th>Tue</th>
<th>Wed</th>
<th>Thu</th>
<th>Fri</th>
<th>Sat</th>
</tr>
<tr>
<th class="bg-danger">8:00-10:00</th>
<td>FS</td>
<td>FWAD</td>
<td>CE</td>
<td>CE</td>
<td>CE</td>
<td>PY</td>
</tr>
<tr>
<th class="bg-danger">10:00-12:00</th>
<td>FWAD</td>
<td>FS</td>
<td>FWAD</td>
<td>FS</td>
<td>FS</td>
<td>CE</td>
</tr>
<tr class="bg-danger">
<th>12:00-1:00</th>
<td colspan="6">LUNCH</td>
</tr>
<tr>
<th class="bg-danger">1:00-3:00</th>
<td>CE</td>
<td>FS</td>
<td>MM</td>
<td>PY</td>
<td>FWAD</td>
<td>FWAD</td>
</tr>
<tr>
<th class="bg-danger">3:00-5:00</th>
<td>PY</td>
<td>PY</td>
<td>FS</td>
<td>FS</td>
<td>PY</td>
<td>FS</td>
</tr>
</table>
<h3>Subjects</h3>
<table class="table table-bordered">
<tr class="bg-danger">
<th>S.No</th>
<th>Subject Code</th>
<th>Subject Name</th>
</tr>
<tr>
<td>1</td>
<td>19AI414</td>
<td>Fundamentals of Web Application Development (FWAD)</td>
</tr>
<tr>
<td>2</td>
<td>19AI301</td>
<td>Python Programming (PY)</td>
</tr>
<tr>
<td>3</td>
<td>SH3414</td>
<td>COMMUNICATIVE ENGLTSH (CE)</td>
</tr>
<tr>
<td>4</td>
<td>ECA-M</td>
<td>Mentor Meet (MM)</td>
</tr>
</table>
<footer>
Designed by ANISH K B | 25019112
</footer>
</body>
</html>
```

## OUTPUT:

<img width="1920" height="1080" alt="Screenshot 2026-04-01 164856" src="https://github.com/user-attachments/assets/14e3f366-8f99-41b0-8c92-1a61e628afa8" />

## RESULT:
A responsive and visually appealing CAMU Schedule web page using Bootstrap is designed successfully.
