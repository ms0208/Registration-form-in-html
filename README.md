# Registration-form-in-html
<!DOCTYPE html>
<html>
<head>
<title> Registration form </title>
<body>
<form>
    <form action ="/action.php">
        <h3 style = "color:blue;">Registration Form of JEE Mains</h3>
        <br>     
    <img src ="https://img.collegepravesh.com/2015/09/NTA-Logo.png">
    <br>
    <br>
    <input type = "text" placeholder="Enter name" height="10" style="color:red;">
    <br>
    <input type = "password"  placeholder ="Enter password" height="10" style="color:blue;">
    <br>
    <input type = "number"    placeholder ="Date of Birth" height="10" style ="color:orangered;">  
    <br>
    <label for = "id1">
        <h3 style="color:blueviolet;"> Enter Class </h3>
        <input type ="radio"value ="Class XI"name = "Class"id="id1"height="5">XI
        <br>    
        <input type ="radio"value ="CLASS XII"name ="Class"id = "id1"height="5">XII
        <br>
        <input type = "radio"value = "Drop year"name = "Drop year"id = "id1"height="5">Drop Year
        <br>
    </label>
    <br>
    <br>
    <h3 style = "color:yellowgreen;">Enter state</h3>
    <br>
    <select name ="City"id ="city" height ="5">
        <br>
        <option value ="Delhi" style = "color:blue;">Delhi</option>  
        <option value ="Mumbai" style = "color:green;">Mumbai</option>  
        <option value ="Chennai" style = "color:yellow;">Chennai</option>  
        <option value ="Banglore" style = "color:palevioletred;">Banglore</option>  
        <option value ="Punjab" style = "color:red;">Punjab</option>
    </select>
    <br>
   <input type ="button" value = "Sumbit" height ="3" style="color:goldenrod;" > 
   </form>
   <br>
   <img src ="https://i.pinimg.com/originals/8c/e7/34/8ce734235905e65eff1ec376b59d483b.jpg" height="100">
</body>
</html>
   
