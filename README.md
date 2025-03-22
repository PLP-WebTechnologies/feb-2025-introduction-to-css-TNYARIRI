# Introduction to CSS

cc

# Tasks
 - Link an external CSS file.
 - Apply at least 3 different selectors.
 - Improve readability and aesthetics.

Happy Coding! 💻✨

<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <meta http-equiv="X-UA-Compatible" content="ie=edge">
    <title>Styled Page</title>
    <link rel="stylesheet" href="style.css">
</head>
<body>
    <div class="container">
        <!-- Header Section -->
        <header id="header">

        </header>

        
        <p class="intro">
            Hello and welcome to my web page. This is the introduction section of the site and provides a bit of information.
</p>

        <!-- Table of Contacts -->
        <h2>Contact List</h2>
        <table>
            <tr>
                <th>Name</th>
<th>Email</th>
                <th>Phone</th>
            </tr>
            <tr>
<td>John Doe</td>
                <td>johndoe@example.com</td>
                <td>+1 234 567 890</td>
            </tr>
<tr>
                <td>

                NOW CSS

                /* Apply general styling for the body */
body {
    font-family: Arial, sans-serif;
    background-color: #f4f4f4;
    margin: 0;
    padding: 0;
}

/* Styling for elements with the class "container" */
.container {
    max-width: 1200px;
    margin: 0 auto;
    padding: 20px;
    background-color: #ffffff;
    border: 1px solid #ddd;
    box-shadow: 0 4px 8px rgba(0, 0, 0, 0.1);
}

/* Apply styles to the header with the ID "header" */
#header {
    background-color: #4CAF50;
    color: white;
    padding: 10px;
    text-align: center;
    font-size: 2em;
}

/* Styling for paragraphs with the class "intro" */
.intro {
    font-size: 1.2em;
    color: #333;
    line-height: 1.6;
    margin-bottom: 20px;
}

/* Add styles for links with the class "btn" */
.btn {
    display: inline-block;
    padding: 10px 20px;
    background-color: #008CBA;
    color: white;
    text-decoration: none;
    border-radius: 5px;
    margin-top: 20px;
}

.btn:hover {
    background-color: #005f73;
}

/* Table styling */
table {
    width: 100%;
    border-collapse: collapse;
    margin-top: 20px;
}

table, th, td {
    border: 1px solid #ddd;
}

th, td {
    padding: 10px;
    text-align: left;
}

th {
    background-color: #f2f2f2;
}

/* Style for the registration form */
form {
    max-width: 500px;
    margin: 20px auto;
    padding: 20px;
    background-color: #ffffff;
    border: 1px solid #ddd;
    border-radius: 8px;
}

form label {
    display: block;
    margin-bottom: 5px;
    font-weight: bold;
}

form input[type="text"],
form input[type="email"],
form input[type="password"] {
    width: 100%;
    padding: 10px;
    margin-bottom: 15px;
    border: 1px solid #ddd;
    border-radius: 4px;
}

form input[type="submit"] {
    background-color: #4CAF50;
    color: white;
    padding: 10px 20px;
    border: none;
    border-radius: 4px;
    cursor: pointer;
}

form input[type="submit"]:hover {
    background-color: #45a049;
}


