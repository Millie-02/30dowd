<!DOCTYPE html>
  <html>
  <body>
  <style>
    body{
      background-image: url(“sunflowers.jpg”);
      background size: 100%;
      background-attachment: fixed;
    }
    header{
      colour: #A9A9A9;
      text-transform: capitalize;
      font-family: “Times New Roman”;
      text-align: center;
      text-decoration: underline;
      border: 2 px double #808080;
      margin: 100px;
    }
    input{
      padding: 10px 10px;
      box-sizing: border-box;
      border: 1px outset #000000;
      font-family: “Times New Roman”;
    }
    input:focus{
      padding: 10 px 20 px;
      background-colour: #D3D3D3;
      border: 2px inset #800000;
      font-family: “Lucida Handwriting”; 
    }
    label{
      text-decoration:underline;
    }
    table{
      border: 2 px solid #000000;
      width: 100%;
      background-colour: hsla(225, 100%, 50%, 0.2);
    }
    td{
      border: 1px solid #808080
      text-align: center;
      font-family: “Times New Roman”;
    }
    th{
      colour: #A9A9A9;
      border: 1px solid #C0C0C0;
      text-align: center;
      font-family: “Times New Roman”;
      text-transform: capitalize;
      text-decoration: underline;
    }
  footer{
    font-family: “Times New Roman”;
    colour: #C0C0C0;
    border: 1px dotted #808080;
   }
 </style>
  <header>
      <h1>Barebones Portfolio</h1>
      <h2>HTML Project</h2>
  </header>
    <form>
      <label for="email"><b>Email:</b></label><br>
      <input type="text" id="email" name="email"><br>
      <label for="phno"><b/>Phone Number:</b></label><br>
      <input type="number" id="phno" name="phno"><br>
      <label for="fname"><b>First name:</b></label><br>
      <input type="text" id="fname" name="fname"><br>
      <label for="lname"><b>Last name:</b></label><br>
      <input type="text" id="lname" name="lname"><br>
      <input type="submit" value="Submit">
      <input type="button" value="OK">
     </form>
     <table>
       <tr>
         <th><b>Email</b></th>
         <th><b>Number</b></th>
         <th><b>First name</b></th>
         <th><b>Last name</b></th>
       </tr>
       <tr>
         <td>debhazra2002@gmail.com</td>
         <td>8250017764</td>
         <td>Deblina</td>
         <td>Hazra</td>
       </tr>
       <tr>
         <td>abxy@yahoo.com</td>
         <td>9999999999</td>
         <td>Abc</td>
         <td>Xyz</td>
       </tr>
     </table>
     <video width="320" height="240" controls>
       <source src="BabyCat.mp4" type="video/mp4" alt="Video of Cute Kitten">
       <i>Your browser does not support the video tag.</i><br>
     </video>
     <footer>
       <p>By Deblina Hazra</p>  
     </footer>
   </body>
   </html>

