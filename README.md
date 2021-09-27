# projectcode.github.io
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta http-equiv="X-UA-Compatible" content="IE=edge">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>menu-icon</title>
    <style>
        *{
            margin:0;
            box-sizing:border-box;
            padding:0;
        }
        .container{
            margin:20px;
        }
        .container > div{
            width:50px;
            height:5px;
            background-color:#000;
            margin-bottom:5px;
            cursor:pointer;
        }
       .change .bar1{
            transform:rotate(-45deg) translate(-9px,6px);
        }
     .change .bar2{
opacity:0;
        }
     .change .bar3{
            transform:rotate(45deg) translate(-8px,-6px);
        }
    </style>
</head>
<body>
    <div class="container" onclick="myfunction(this)">
        <div class="bar1"></div>
        <div class="bar2"></div>
        <div class="bar3"></div>
    </div>
    <script>
        function myfunction(x)
        {
            x.classList.toggle("change");
        }
    </script>
</body>
</html>
