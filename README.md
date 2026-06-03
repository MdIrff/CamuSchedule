# Ex08 CAMU Schedule using Bootstrap
## Date:

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
Add the Bootstrap CDN link inside the <head> section.

### Step 5:
Insert a table element with Bootstrap table classes.

### Step 6:
Construct the complete table.

### Step 7:
Add a header/footer displaying copyright information.

### Step 8:
Publish the website in the LocalHost.

## PROGRAM :
````
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1">
    <title>CAMU Schedule</title>

    <!-- Bootstrap CSS -->
    <link rel="stylesheet" href="https://maxcdn.bootstrapcdn.com/bootstrap/3.4.1/css/bootstrap.min.css">

    <style>
        body {
            background-color: #f5f5f5;
            padding-top: 30px;
        }

        .panel-heading {
            text-align: center;
            font-size: 24px;
            font-weight: bold;
        }

        .student-info {
            margin-bottom: 20px;
            font-size: 16px;
        }

        table {
            background-color: #fff;
        }

        th {
            text-align: center;
            background-color: #337ab7;
            color: white;
        }

        td {
            text-align: center;
            vertical-align: middle !important;
        }

        .footer-text {
            text-align: center;
            margin-top: 15px;
            color: #666;
        }
    </style>
</head>
<body>

<div class="container">

    <div class="panel panel-primary">

        <div class="panel-heading">
            CAMU Weekly Schedule
        </div>

        <div class="panel-body">

            <div class="student-info">
                <strong>Course:</strong> CSE <br>
                <strong>Semester:</strong> Current Semester
            </div>

            <div class="table-responsive">

                <table class="table table-bordered table-striped table-hover">

                    <thead>
                        <tr>
                            <th>Day</th>
                            <th>Time</th>
                            <th>Course Code</th>
                            <th>Course Name</th>
                        </tr>
                    </thead>

                    <tbody>

                        <tr>
                            <td>Monday</td>
                            <td>10:00 AM - 12:00 PM</td>
                            <td>19CS405</td>
                            <td>Operating System</td>
                        </tr>

                        <tr>
                            <td rowspan="2">Tuesday</td>
                            <td>10:00 AM - 12:00 PM</td>
                            <td>19AI414</td>
                            <td>Fundamentals of Web Application</td>
                        </tr>

                        <tr>
                            <td>01:00 PM - 03:00 PM</td>
                            <td>19AI414</td>
                            <td>Fundamentals of Web Application</td>
                        </tr>

                        <tr>
                            <td rowspan="3">Wednesday</td>
                            <td>08:00 AM - 10:00 AM</td>
                            <td>19CS405</td>
                            <td>Operating System</td>
                        </tr>

                        <tr>
                            <td>10:00 AM - 12:00 PM</td>
                            <td>19AI414</td>
                            <td>Fundamentals of Web Application</td>
                        </tr>

                        <tr>
                            <td>01:00 PM - 03:00 PM</td>
                            <td>ECA-M</td>
                            <td>Mentor Meet</td>
                        </tr>

                        <tr>
                            <td>Thursday</td>
                            <td>08:00 AM - 10:00 AM</td>
                            <td>19CS405</td>
                            <td>Operating System</td>
                        </tr>

                        <tr>
                            <td rowspan="2">Friday</td>
                            <td>08:00 AM - 10:00 AM</td>
                            <td>19CS405</td>
                            <td>Operating System</td>
                        </tr>

                        <tr>
                            <td>10:00 AM - 12:00 PM</td>
                            <td>19AI414</td>
                            <td>Fundamentals of Web Application</td>
                        </tr>

                        <tr class="warning">
                            <td>Saturday</td>
                            <td colspan="3">
                                <strong>No Classes</strong>
                            </td>
                        </tr>

                    </tbody>

                </table>

            </div>

        </div>

    </div>

    <div class="footer-text">
        © 2026 CAMU Schedule - Bootstrap Assignment
    </div>

</div>

<!-- jQuery -->
<script src="https://ajax.googleapis.com/ajax/libs/jquery/3.7.1/jquery.min.js"></script>

<!-- Bootstrap JS -->
<script src="https://maxcdn.bootstrapcdn.com/bootstrap/3.4.1/js/bootstrap.min.js"></script>

</body>
</html>
````



## OUTPUT:
<img width="1882" height="944" alt="Screenshot 2026-06-03 101521" src="https://github.com/user-attachments/assets/e553539b-4832-4f93-916e-c66ed75b8246" />



## RESULT:
A responsive and visually appealing CAMU Schedule web page using Bootstrap is designed successfully.
