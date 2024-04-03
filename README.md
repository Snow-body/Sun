### Sun
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta http-equiv="X-UA-Compatible" content="IE=edge">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title> Test logic</title>
</head>
<body>
    <div class="home">
      <div class="snow">
        <input class="Scorpion" type="Number">
        <p class="Siu"> + </p>
        <input class="Sun" type="Number"> 
        <button class="do-list" onclick="Brazil"> Som </button>
      </div>
      <input class="Su" type="Number"> 
      </div>
  <script>
var Moon = Number.parseInt(window.document.querySelector('.Scorpion'));
var Space = Number.parseInt(window.document.querySelector('.Sun'));
var S= Moon + Space;
var Star =  Number.parseInt(window.document.querySelector('.Su'));
 function Brazil(){
 Star.innerHtml = S;
 }   
  </script>
</body>
</html>


<!DOCTYPE html>
<html lang="">
<head>
    <meta charset="UTF-8">
    <meta http-equiv="X-UA-Compatible" content="IE=edge">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title> Cadastramento para a UJES da Faculdade de Economia</title>
    <link rel="stylesheet" href="Account.CSS">
    <link href='https://unpkg.com/boxicons@2.1.4/css/boxicons.min.css' rel='stylesheet'>
    <link rel="stylesheet" href="https://uxwing.com/x-social-media-black-icon/">
    <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.5.1/css/brands.min.css" integrity="sha512-8RxmFOVaKQe/xtg6lbscU9DU0IRhURWEuiI0tXevv+lXbAHfkpamD4VKFQRto9WgfOJDwOZ74c/s9Yesv3VvIQ==" crossorigin="anonymous" referrerpolicy="no-referrer" />
    <link rel="stylesheet" href="https://www.flaticon.com/icons">
</head>
<body class="">
    <header class="header">
    <nav class="navbar">
<a href="#"> Informações sobre</a>
<a href="#"> Serviços </a>
<a href="#"> Sobre nós </a>
<a href="#"> Contactos</a>
    </nav>
<!--EMP --> 
<em draggable="true"></em>
    <form action="#" class="search-bar">
        <input type="text" class=""  placeholder="pesquisa...">
<button type="submit" class="row">  <i class='bx bx-search-alt-2'></i>  </button>
    </form>
</header>
<!-- Composição Lírica -->
<div class="background"></div>
<div class="container">
    <div class="content">
        <h2 class="logo">   <i class="bx bx1-firebase">
        </i> <!-- por tempos deixar de ser --> Faculdade De Economia </h2>
        
        <div class="text-sci">
        <h2> Bem-Vindo!  <br> <span> a subscrição da UJES! </span></h2>
          <p> <!-- Lorem ipsum dolar site amet consectetur adipisicing elit. 
              voluptatum, unde.--> Para um futuro melhor, para um futuro sem rasteiras, saiba onde estar e como caminhar... </p>
        
        <div class="social-icons">
        <a href="#" > <i class='bx bxl-facebook-circle'> </i></a>
        <a href="#">  <i class='bx bxl-instagram'> </i></a>
        <a href="#">  <i class='bx bxl-whatsapp'></i>  </a>
        <a href="#">  <img src="IMG/download.png" alt="" class="dtw"></a>
                 </div>
             </div>
        </div>
        
        <div class="logreg-box" id="History">

       
        </div>
        
        
        </div>
</div>

<script>

var Sun = document.querySelector('#History');

Sun.innerHTML =  `    
 <div class="form-box login">
        <form action="#" class="">
            <h2 > Inscrever-se </h2>
           <div class="input-box">
               <span class="icon">
                   <i class='bx bxs-envelope'></i>
                </span>
         <input type="email" name="" required>
         <label for=""> Email </label>
        
        </div>
        
        <div class="input-box">
        <span class="icon">
            <i class='bx bxs-low-vision' id="surf" onclick="dash()">
        </i>
        </span>
         <input type="password" id="ann" name="" required>
         <label for="" > Palavra-passe </label>
        
        </div>
        
        <div class="input-box">
            <span class="icon">
                <i class='bx bxs-lock-open-alt'></i>
            </span>
         <input type="text" id="ann" name="" required>
                <label for=""> Confirmar Passe </label>
            </div>
        
        <div class="input-box">
            <span class="icon">
                <i class='bx bxs-user-circle'></i>
            </span>
        <input type="text" name="" required>
        <label for=""> Nome </label> 
        </div>
        <div class="input-box">
            <span class="icon"> 
                 <i class='bx bxs-id-card'></i>
            </span>
            <input type="password" id="ann" name="" required>
             <label for=""> Bilhete de Identidade </label>     
             </div>
              <div class="remember-forgot">
           
        </div>
        <button type="submit" class="btn" onclick="clock()" aria-required="true">
        Proseguir
         </button>
        <div class="login-register">
          <a href="../Demo.HTML"> <p> Já possuo uma conta ! </p></a> 
        </div>
        
        </form>
        
             `;

             function clock() {
                 Sun.innerHTML =    `   
                  <div class="form-box login">
        <form action="#" class="">
            <h2 > Inscrever-se </h2>
           <div class="input-box">
               <span class="icon">
                   <i class='bx bxs-home'></i>
                </span>
         <input type="email" name="" required>
         <label for=""> Morada </label>
        
        </div>
        
        <div class="input-box">
        <span class="icon">
            <i class='bx bxs-phone-call'></i>
        </i>
        </span>
         <input type="password" id="ann" name="" required>
         <label for="" > Contacto </label>
        
        </div>
        
        <div class="input-box">
            <span class="icon">
                <i class='bx bxs-lock-open-alt'></i>
            </span>
         <input type="texto" id="ann" name="" required>
                <label for=""> Ano  </label>
            </div>
        
        <div class="input-box">
            <span class="icon">
                <i class='bx bxs-user-circle'></i> <i class="fi fi-brands-java"></i>
            </span>
        <input type="text" name="" required>
        <label for=""> Nome </label> 
        </div>
        <div class="input-box">
            <span class="icon"> 
        <select name="" id="">
        
   <option value="">  Primeiro</option>
    <option value=""> Segundo</option>
    <option value=""> Terceiro</option>
    <option value=""> Quarto </option>
    <option value=""> Quinto</option>
</select>
            </span>
            <input type="password" id="ann" name="" required>
             <label for=""> Curso e ano de ingresso </label>     
             </div>
             <div class="remember-forgot">
           
        </div>
        <button type="submit" class="btn" onclick="clock()">
            Subcrever
         </button>
        <div class="login-register">
          <a href="../Demo.HTML"> <p> Já possuo uma conta ! </p></a> 
        </div>
        
        </form>
             `;

             } 

/* 
var Snoop = ['Download ', 'Hello' , 'Drogs'];
Snoop[2] = 'Love';
window.prompt("" + Snoop);

function clock() {
var Moon = document.querySelector('#History');
Moon.innerHTML = 'Love';
}*/

</script>

</body>
