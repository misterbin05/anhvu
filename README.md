<!DOCTYPE html>  
<html lang="en">  
<head>  
    <meta charset="UTF-8">  
    <meta name="viewport" content="width=device-width, initial-scale=1.0">  
    <title>Chuyển động Hình Vuông</title>  
    <link rel="stylesheet" href="styles.css">  
</head>  
<body>  
    <div class="square"></div>  
</body>  
</html>
body {  
    display: flex;  
    justify-content: center;  
    align-items: center;  
    height: 100vh;  
    margin: 0;  
    background-color: #f0f0f0;  
}  

.square {  
    width: 100px;  
    height: 100px;  
    background-color: #3498db;  
    position: relative;  
    animation: move 2s infinite alternate;  
}  

@keyframes move {  
    0% {  
        transform: translateX(0);  
    }  
    100% {  
        transform: translateX(300px);  
    }  
}
