<script>
    let texto = ''
    let password= ''
  </script>
  
  <main>
    <div class="body-input">
     <input type="text" bind:value={texto}  placeholder="Email">
      <input type="password" bind:value={password}  placeholder="Contraseña">
    </div>
      <div class="login">
        <h1 class="headerlogin">BANCO MADOFF</h1>
        <img src="imagenes/Logo.png" class="logologin" alt="">
        <h2 class="h2"> Inicio de sesion </h2>
        <p class="p">¿Se te olvido tu contraseña?</p>
        <div class="link">
          <ol><a href="#Contacto">!Contactanos¡</a></ol>
          <ol><a href="#TerminosyCondiciones">Terminos y Condiciones</a></ol>
          <ol><a href="#Nosotros">Nosotros</a></ol>
        </div>
        <button class="botonlogin">Ingresar</button>
      </div>
  </main>
  
  <style>
    .h2{
      position: absolute;
      left: 680px;
      top: 300px;
      }
      
      .p{
      position: absolute;
      left: 670px;
      top: 560px;
      }
      
      .link{
      position: absolute;
      text-align: center;
      width: 230px;
      height: 77px;
      
      left: 640px;
      top: 600px;
      }
  
      .botonlogin{
      position: absolute;
      left: 730px;
      top: 520px;
      }
  
      .logologin{
      position: absolute;
      left: 720px;
      top: 190px;  
      }
  
      .headerlogin{
      position: absolute;
      left: 605px;
      top: 20px;
      }
  
      .body-input input{
      display: block;
      margin: auto;
      height: 40px;
      width: 18%;
      padding-left: 10px;
      color:black;
      border: 1px solid #000;
      border-radius: 2px;
      background-color: transparent;
      border-radius:10px ;
  
      position: absolute;
      text-align: center;
      left: 630px;
      top: 400px;    
  
      }
      .body-input input[type="password"]{
  
      position: absolute;
      text-align: center;
      left: 630px;
      top: 450px;   
      }
  
  </style>