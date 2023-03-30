<!doctype html>
<html>
<head>
 <title></title>
 <link rel="stylesheet" href="style.css">
<meta charset="UTF-8">  <meta name="viewport" content="width=device-width, initial-scale=1.0"> 
</head>
<body>
<center><input type="text" name="" alt="search" pattern="[a-z]*" placeholder="Enter Name" class="inp"></center>
<style>
 body {
 background-color: #000;
}
.inp {
 color: #fff;
 width: 170px;
 height: 27px;
 outline: none;
 text-align: center;
 text-decoration: none;
 border-top: none;
 border-left: none;
 border-right: none;
 border-radius: 10px;
 border-bottom: 2px solid hsla(209, 100%, 54%, 1);
 transform: translateY(270px);
 transition: 0.5s;
 background: transparent;
}
.inp:hover {
 border: 2px solid hsla(131, 100%, 66%, 1);
}
.inp:invalid {
 border: 2.5px solid hsla(7, 100%, 59%, 1);
 animation: drainxer 0.2s 2;
 }
 @keyframes drainxer {
  25% {translate: 6px 0;}
  50% {translate: -6px 0;}
  75% {translate: 6px 0;}
 }
}
</style>
 <script src="script.js"></script>
</body>
</html>
