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

Answer
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Document</title>
    <style>
        table{
            border-collapse: collapse;
            width: 100%;
        }
        th, td {
            border: 1px solid #ddd;
            padding: 8px;
            text-align: left;
        }
        th{
            background-color: #f2f2f2;
            font-weight: bold;
        }
        tr:nth-child(even){
            background-color: #f9f9f9;
        }
    </style>
</head>
<body>
   <h1>Ordered List</h1> 
   <ol>
    <li>
        I = 1
    </li>
    <li>II = 2</li>
    <li>III = 3</li>
    <li>IV = 4</li>
    <li>V = 5</li>
   </ol>
   <h2>Image</h2>
   <img src="https://images.pexels.com/photos/31363711/pexels-photo-31363711/free-photo-of-young-boy-exploring-urban-architecture-in-berlin.jpeg?auto=compress&cs=tinysrgb&w=600&lazy=load"
   width="300px" alt="nature">
   <h3>Table</h3>
   <table>
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
        <td>Riziki</td>
        <td>Makueni</td>
        <td>0709876523</td>
        <td>riziki@gmail.com</td>
    </tr>
    <tr>
        <td>Brenda</td>
        <td>Machakos</td>
        <td>0700000054</td>
        <td>brenda@gmail.com</td>
 </tr>
 <tr>
    <td>Risper</td>
    <td>Nairobi</td>
    <td>0756542806</td>
    <td>rislind@gmail.com</td>
 </tr>
 <tr>
    <td>Stecy</td>
    <td>Kisumu</td>
    <td>0123456789</td>
    <td>stecy003@gmail.com</td>
 </tr>
 </tbody>
   </table>
   <h4>Registration Form</h4>
</body>
</html>
