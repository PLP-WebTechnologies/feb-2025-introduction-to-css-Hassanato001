# Introduction to CSS

## Objectives
Link an external CSS file to an HTML document.
Apply basic styling using selectors.
Use colors, fonts, and spacing effectively.

## Instructions

Create a style.css file.
Apply CSS to a HTML page.
Style elements using:
Classes and IDs.
Color and typography.
Margins, paddings, and borders.

>[!NOTE]
>  - Include at least:
>  - Use of 3 selectors
>  - Style an image
>  - Margin, Padding & Borders
>  - Different font

# Tasks
 - Link an external CSS file.
 - Apply at least 3 different selectors.
 - Improve readability and aesthetics.

Happy Coding! 💻✨

<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1, maximum-scale=1, user-scalable=no">
    <link rel="stylesheet" href="style.css">
    <meta name="description" content="A comprehensive HTML5 project demonstrating the use of images, lists, tables, forms, and multimedia elements.">
    <meta name="keywords" content="HTML5, images, lists, tables, forms, multimedia, web development">
    <meta name="author" content="Abu Musa">
    <meta name="robots" content="index, follow">

 <title>signup</title>
 
<style>
table ,tr, th, td { 
   border: 3px solid black ; 
   border-collapse: collapse;  
   text-align: center ;
   padding: 10px ;
        }
</style>

</head>
<body>
    <header>
    <p style="background-color: aqua; font-size: medium; color: rgb(211, 178, 178); text-align: center;">IN THIS ASSIGNMENT I WOULD BE WORKING ON THE FOLLOWING</p>
   <nav>
 

   <a href="#images"> <li> Implementing HTML5 images </li></a>  
     <a href="#lists"> <li> Implementing HTML5 lists</li></a> 
     <a href="#tables"> <li> Implementing HTML5 tables</li></a>
     <a href="#forms"> <li> Implementing HTML5 forms and input types </li></a>     

  </nav>
     </header>

<main>
    <section id="images">
   <h2> Implementing HTML5 images </h2>
<figure>
     <img src="pexel.jpg" alt="An IPhone image" width="150" height="100" >
     <figcaption>An IPhone image</figcaption>
</figure>
 <p> Another image is displayed here </p>
 <figure>
<img src="pexel2.jpg" alt="Phone accessories" width="150" height="100">
   <figcaption>Some Phone accessories</figcaption>
</figure>
<p>FOR MORE IMAGES </p>
<figure>
 <a href="https://www.pexels.com/"><img src="me.jpg" alt="PEXEL SITE " width="50"></a>
 <figcaption style="background-color: aqua; width: 30%; border-radius: 8px;
 margin: 10px auto;
 display: block; ">PEXEL SITE </figcaption>
</figure>
   </section>

   <section id="lists">
   <h2> Implementing HTML5 lists</h2>
   <p>Here are the skills that I have learnt and would love to make furtune from</p>
   <ol style="list-style-type: upper-roman;">
<li>HTML</li>
<li>CSS</li>
<li>PYTHON</li>
<li>Artificial Intelligence and Machine Learning</li>
<li>Also wants to venture into Javascript</li>
   </ol>
  </section>
  <section id="tables">
    <h2>Implementing HTML5 tables</h2>
<table  >
   <thead>
        <tr>
            <th> S/N</th>
            <th> Surn Name</th>
            <th> First Name</th>
            <th> Addresss</th>
            <th> Mobile  </th>
            <th> Emails</th>
        </tr>
    </thead>
    <tbody>
<tr>
    <th>1</th>
    <td>HASSAN</td>
    <td>AHMAD</td>
    <td> F division off Tipper Garage,Ilorin</td>
    <td>07077427778</td>
    <td>ahmad567@email.com</td>
</tr>

<tr>
    <th>2</th>
    <td>SULAIMAN</td>
    <td>HASSAN</td>
    <td>Unilorin Road, Ilorin</td>
    <td>08032223345</td>
    <td>imam234@yahoomail.com</td>
</tr>

<tr>
    <th>3</th>
    <td>ABDURRAHMAAN</td>
    <td>ABDURRASAQ</td>
    <td>Olunlade, Idi Ogede Ilorin</td>
    <td>08156694383</td>
    <td>rasaqi786@email.com</td>
</tr>
<tr>
    <th>4</th>
    <td>ABDUSSALAAM</td>
    <td>RASHEEDAH</td>
    <td>Sanraab, Tanke Ilorin</td>
    <td>08064891498</td>
    <td> abdulsalam@gmail.com</td>
</tr>
    </tbody>
     </table>

   </section>


   <section id="forms">
   <h2>Implementing HTML5 forms and input types</h2>
        <form action="" method="post"> 
            <fieldset>
                <legend>REGISTRATION FORM</legend>
                <p>
                    <label for="fname">FULLNAME</label>
                    <input type="text" id="fname" name="fullname" placeholder="AHMAD" autocomplete="on" required autofocus>
                </p>
                <p>        
                    <label for="sname">SURNAME</label>
                    <input type="text" id="sname" name="surname" placeholder="HASSAN" autocomplete="on" required>
                </p>
                <p>       
                    <label for="email">EMAIL</label>
                    <input type="email" id="email" name="email" placeholder="ME@gmail.com" autocomplete="on" required>
                </p>  
                <p>       
                    <label for="password">ENTER PASSWORD</label>
                    <input type="password" id="password" name="password" placeholder="ENTER PASSWORD" minlength="8" required>
                </p>  
                <p>         
                    <label for="date">DATE</label>
                    <input type="date" id="date" name="date" required>
                </p>  
                <p>
                    <label for="gender">GENDER</label>
                    <input type="radio" id="male" name="gender" value="male" required> Male
                    <input type="radio" id="female" name="gender" value="female" required> Female
                </p>
                <p>
                    <label for="country">COUNTRY</label>
                    <select id="country" name="country" required>
                        <option value="">Select your country</option>
                        <option value="nigeria">Nigeria</option>
                        <option value="uksa">Saudi Arabia</option>
                        <option value="albania">Albania</option>
                        <option value="pak">Pakistan</option>
                    </select>
                </p>
                <p>
                    <label for="terms">AGREE TO TERMS</label>
                    <input type="checkbox" id="terms" name="terms" required> I agree to the terms and conditions
                </p>
                <p>
                    <input type="submit" value="SIGNUP" name="submit" id="submit">
                </p> 
            </fieldset>      
   </form>
   </section>
</main>
<footer>
 
</footer>    
</body>

<footer style="background-color: aqua; font-size: medium; color: rgb(211, 178, 178); text-align: center;">
    <p>&copy; 2023 Abu MUsa. All rights reserved.</p>
</footer>

</html>

body {
    background-image: url(amr1.jpg) ;
    background-repeat: no-repeat;
    background-attachment: fixed;
    color: rgb(212, 193, 171);
    font-weight: normal;
    text-align: center;
    position: relative;
    padding: 12px 15px  ;
     
}


header {
    background-color: #1b273d; /* Green */
    padding: 20px;
    text-align: left;
    font-size: 15px;
    color: rgb(241, 239, 239);
}
h2 { 
    background-color: aqua;
    text-align: center;

}

#forms {
   
    background-color: #1b273d; /* Green */
    font-size: 15px;
    font-weight: 40px;
}
    a:hover, a:active {
   background-color: lightblue;
        padding:2px 3px 2px 3px;
        }
        a:visited{
        color: rgb(212, 197, 197);
        } 
#submit {
    background-color: #3009db; /* Green */
    border: none;
    color: rgb(43, 25, 143);
    padding: 8px 12px;
    text-align: center;
    font-size: 12px;
    font-size:8px;
    margin: 4px 2px;
    cursor: pointer;
    border-radius: 6px;
}
img {
    width: 300px;
    height: auto;
    border: 3px solid #1b273d;
    border-radius: 8px;
    margin: 10px auto;
    display: block;
}

p {
    font-family: 'Arial', sans-serif;
    font-size: 16px;
    line-height: 1.5;
    margin: 10px 20px;
    color: rgb(200, 200, 200);
}

.container {
    padding: 20px;
    margin: 20px auto;
    border: 2px dashed #1b273d;
    border-radius: 12px;
    background-color: rgba(27, 39, 61, 0.8);
    max-width: 800px;
}

