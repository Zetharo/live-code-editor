Podes probrar que funciona con este codigo:

# HTML:
 1- Crear un div con la class="container".
 2- Luego dentro del div un button con el evento onclick="changeColor(this)" conteniendo el texto que nosotros queramos.
 3- Cerramos el div.
 

# CSS:
button{
background: red;
padding: 20px;
font-size: 20px;
color: #fff;
margin: 200px;
border-radius: 8px;
}
.container{
height: 100%;
width: 100%;
display: flex;
justify-content: center;
align-items: center;
}

# JavaScript:
function changeColor(x){
x.style.background = "black"
}
