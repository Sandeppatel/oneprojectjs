# oneprojectjs
js my first project
## html

<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Document</title>
    <link rel="stylesheet" href="project1.css">
</head>
<body>
    <div id="clock"></div>
    <script src="project1.js"></script>
</body>
</html>

## css

*{
    margin: 0;
    padding: 0;
    box-sizing: border-box;
}
html , body{
    height: 100%;
    width: 100%;
}
 body{
    height: 100%;
    width: 100%;
    display: flex;
    align-items: center;
    justify-content: center;

}
.clock{
    padding: 30px 60px;
    background-color: gray;
}


## js


const clock = document.getElementById('clock')


setInterval(function () {
    let date = new Date();
    clock.innerHTML = date.toLocaleTimeString();
   
}, interval);
