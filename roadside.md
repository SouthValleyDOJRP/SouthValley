<html>
<style>
body {
background-color: black;
}


img {
  animation: rotation 6s infinite linear;
  display: block;
  margin: auto;
  color: black;
  background-color: black;
  vertical-align: middle;
}

@keyframes rotation {
  from {
    transform: rotate(0deg);
  }
  to {
    transform: rotate(359deg);
  }
}

p1 {
display: block;
text-align: center;
font-size: xx-large;
color: white;
vertical-align:top
}

p2 {
display: block;
text-align: center;
font-size: xx-large;
color: white;
vertical-align: bottom;
}
</style>
<body>



<p1>Calling your local mechanic, they will answer if they are not busy!</p1>
<br>
<img src="img/wrenches.png">
<br>
<p2>Please wait, It won't pop up but they are being called!</p2>
</body>

</html>