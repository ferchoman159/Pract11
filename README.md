<!DOCTYPE html>
<html lang="en">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<meta http-equiv="X-UA-Compatible" content="ie=edge">
<meta name="Description" content="Enter your description here"/>
<link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/twitter-bootstrap/4.5.2/css/bootstrap.min.css">
<link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/5.15.0/css/all.min.css">
<title>Creacion de menu</title>
</head>
<style>
    body{
    background-color: black;
    padding-top: 2em;
}
.desplazamiento{

    margin-left:30%;

  
}
.hola{
    display: inline-block; 
}
.principal{

    background-color: olive;
    max-width: 80%;
    min-height: 500px;
    margin: auto;
    padding-top: 10px; 
}

.menu{
    text-decoration: none;
    background-color: #c0c0c0;
}

.menu li{
    
}

.menu ul, .menu li{
list-style: none;
float: left;
padding-left: 2em;
color: yellow;
display: block;
}

.menu li a{
    color: white;
    
}

.menu li a:hover{
   
    text-decoration: none;
    color: black;
    font-size: small;
    background-color: cornflowerblue;
}
</style>
<body>
    <div class="principal">
        <nav class="menu">
            <ul class="desplazamiento">
                <li><a href="#">Inicio</a></li>
                <li><a href="#">Paginas</a></li>
                <li><a href="#">Informacion</a></li>
                <li><a href="#">Acerca de...</a></li>
                <li><a href="#">algun texto</a></li>
            </ul>
        </nav>
        <main class="hola">
            Lorem ipsum dolor sit amet consectetur adipisicing elit. Corrupti illum ducimus quos earum. Eveniet quos obcaecati sint aliquam cupiditate, minus beatae facilis hic sit? Commodi maiores eius ipsam iste assumenda!Ab quo fugit sit, deserunt iure dolore incidunt veritatis a eius, blanditiis, est reprehenderit. Enim vitae neque culpa fugiat soluta? Dolores, repellendus veritatis eius labore autem ad tempora quia voluptatum.
        </main>
            
    </div>
<script src="https://cdnjs.cloudflare.com/ajax/libs/jquery/3.5.1/jquery.slim.min.js"></script>
<script src="https://cdnjs.cloudflare.com/ajax/libs/popper.js/1.16.1/umd/popper.min.js"></script>
<script src="https://cdnjs.cloudflare.com/ajax/libs/twitter-bootstrap/4.5.2/js/bootstrap.min.js"></script>
</body>
</html>
