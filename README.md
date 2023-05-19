Podes probrar que funciona con este codigo:

# HTML:
# <div class="container">
# <button onclick="changeColor(this)"> HELLO WORLD! </button>
# </div>

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
