# index.html<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Student Dashboard</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            margin: 0;
            padding: 0;
            background-color: #f3f3f3;
        }

        .header {
            background-color: #02457A;
            color: white;
            padding: 15px;
            text-align: center;
            font-size: 22px;
            font-weight: bold;
        }

        .gpa-container {
            text-align: center;
            margin: 15px;
            font-size: 18px;
            color: #02457A;
        }

        .dashboard {
            display: flex;
            flex-wrap: wrap;
            justify-content: center;
            gap: 10px;
            padding: 10px;
        }

        .class-card {
            background: white;
            width: 160px;
            padding: 10px;
            border-radius: 8px;
            box-shadow: 0px 2px 5px rgba(0, 0, 0, 0.2);
            text-align: center;
            font-size: 16px;
            font-weight: bold;
            position: relative;
        }

        .class-card input {
            width: 100%;
            padding: 5px;
            font-size: 16px;
            text-align: center;
            border: none;
            font-weight: bold;
            background: transparent;
        }

        .grade {
            font-size: 28px;
            font-weight: bold;
            margin: 5px 0;
        }

        .footer {
            position: fixed;
            bottom: 0;
            width: 100%;
            background-color: #02457A;
            color: white;
            text-align: center;
            padding: 10px;
            display: flex;
            justify-content: space-around;
        }

        .footer div {
            cursor: pointer;
            padding: 5px;
        }
    </style>
</head>
<body>

    <div class="header">Dashboard</div>

    <div class="gpa-container">
        <strong>GPA:</strong> <input type="text" id="gpaInput" placeholder="Enter GPA">
    </div>

    <div class="dashboard">
        <div class="class-card" style="background: #8B5CF6; color: white;">
            Jewelry I  
            <input type="text" class="grade-input" placeholder="Enter %">
        </div>

        <div class="class-card" style="background: #10B981; color: white;">
            Prin of Agriculture B  
            <input type="text" class="grade-input" placeholder="Enter %">
        </div>

        <div class="class-card" style="background: #F59E0B; color: white;">
            Prin of Entrepreneurship  
            <input type="text" class="grade-input" placeholder="Enter %">
        </div>

        <div class="class-card" style="background: #14B8A6; color: white;">
            Integrated Chem-Phys  
            <input type="text" class="grade-input" placeholder="Enter %">
        </div>

        <div class="class-card" style="background: #EC4899; color: white;">
            Algebra I:B  
            <input type="text" class="grade-input" placeholder="Enter %">
        </div>

        <div class="class-card" style="background: #EF4444; color: white;">
            English 10 A:B  
            <input type="text" class="grade-input" placeholder="Enter %">
        </div>
    </div>

    <div class="footer">
        <div>🏠 Dashboard</div>
        <div>📚 Classes</div>
        <div>📅 Calendar</div>
        <div>🕒 Schedule</div>
    </div>

</body>
</html>
