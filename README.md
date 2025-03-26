# Advanced HTML5 Elements and Forms

## Objectives
Implement HTML5 images, lists, tables, forms and input types.
Use form validation attributes.
Apply multimedia elements such as audio and video.

## Instructions

- Create an index.html file.
- Add an ordered list with roman numerals
- Add an external image from pexels.com
- Add a table of 5 contacts with; name, address, mobile and emails
- Add a registration form

>[!NOTE]
>  The registration form should have:
>- Name, email, password, and date fields.
>- A dropdown, radio buttons, and checkboxes.
>- Proper labels and placeholders.
>- Required fields and validation attributes.
>- Ensure proper indentation and commenting.
 
# Tasks
- Create a well-structured HTML5 document.
- Ensure semantic correctness.

Happy Coding! 💻✨







//index.html file 
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Contact List & Registration</title>
    <link rel="stylesheet" href="styles.css"> <!-- Link to external CSS if needed -->
</head>
<body>
    <!-- Ordered List with Roman Numerals -->
    <h2>Ordered List</h2>
    <ol type="I">
        <li>Naima Noah</li>
        <li>Kassim Ahmed</li>
        <li>Sharon Mwikeli</li>
        <li>Kibaki Were</li>
        <li>Wafula John</li>
    </ol>
    
    <!-- External Image from Pexels -->
    <h2>Image from Pexels</h2>
    <img src="https://images.pexels.com/photos/414612/pexels-photo-414612.jpeg" alt="Pexels Image" width="600">
    
    <!-- Contacts Table -->
    <h2>Contact List</h2>
    <table border="1">
        <thead>
            <tr>
                <th>Name</th>
                <th>Address</th>
                <th>Mobile</th>
                <th>Email</th>
            </tr>
        </thead>
        <tbody>
            <tr>
                <td>Naima Noah</td>
                <td>Ruiru</td>
                <td>+254 0712345678</td>
                <td>naimanoah32@gmail.com</td>
            </tr>
            <tr>
                <td>Jane Smith</td>
                <td>Kabarnet</td>
                <td>+2540765432198</td>
                <td>jane123@gmail.</td>
            </tr>
            <tr>
                <td>Michael Brown</td>
                <td>789 Pine Rd</td>
                <td>+1122334455</td>
                <td>michael@example.com</td>
            </tr>
            <tr>
                <td>Emily Davis</td>
                <td>Nairobi</td>
                <td>+254 0795836274</td>
                <td>emily@gmail.com</td>
            </tr>
            <tr>
                <td>David Wilson</td>
                <td>Eldoret</td>
                <td>+25407387636</td>
                <td>david45@gmail.com</td>
            </tr>
        </tbody>
    </table>
    
    <!-- Registration Form -->
    <h2>Registration Form</h2>
    <form action="#" method="POST">
        <label for="name">Full Name:</label>
        <input type="text" id="name" name="name" placeholder="Enter your full name" required>
        <br><br>
        
        <label for="email">Email:</label>
        <input type="email" id="email" name="email" placeholder="Enter your email" required>
        <br><br>
        
        <label for="password">Password:</label>
        <input type="password" id="password" name="password" placeholder="Enter your password" required>
        <br><br>
        
        <label for="dob">Date of Birth:</label>
        <input type="date" id="dob" name="dob" required>
        <br><br>
        
        <label for="gender">Gender:</label>
        <input type="radio" id="male" name="gender" value="Male"> Male
        <input type="radio" id="female" name="gender" value="Female"> Female
        <br><br>
        
        <label for="country">Country:</label>
        <select id="country" name="country" required>
            <option value="">Select a country</option>
            <option value="USA">USA</option>
            <option value="UK">UK</option>
            <option value="Canada">Canada</option>
            <option value="Australia">Australia</option>
        </select>
        <br><br>
        
        <label>Interests:</label>
        <input type="checkbox" name="interests" value="Coding"> Coding
        <input type="checkbox" name="interests" value="Sports"> Sports
        <input type="checkbox" name="interests" value="Music"> Music
        <br><br>
        
        <input type="submit" value="Register">
    </form>
</body>
</html>

