<!DOCTYPE html>
<html>
  <head>
    <meta charset="utf-8">
    <meta name="viewport" content="width=device-width">
    <title>Ice Cream</title>
    <link href="style.css" rel="stylesheet" type="text/css" />
  </head>
  <body>
<script>

   function callSomeFunction(){
let strColor = document.getElementById("color").value

if(strColor == "green"){
console.log("go")
}

if(strColor == "red"){
  console.log("stop")
}
if(strColor == "yellow"){
  console.log("hurry up and make that damn light")
   }
}

  </script>
    <script src="script.js"></script>

<select onchange="callSomeFunction()" id="color">
  <option value="">Select a color</option>
  <option value="red">Red</option>
  <option value="yellow">Yellow</option>
  <option value="green">Green</option>
</select>
  </body>
</html>
