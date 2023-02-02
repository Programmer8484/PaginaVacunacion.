# PaginaVacunacion.

PracticaCSS. Es una página de vacunación con HTML, CSS y es responsiva.

<!DOCTYPE html>
<html lang = "en">
<head>
    <meta charset = "UTF-8">
    <meta http-equiv="X-UA-Compatible" content="IE=edge">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Vacunación.</title>
    <link rel="stylesheet" href="./PagVacunación.css">
    <script src="https://kit.fontawesome.com/c2f035752e.js" crossorigin="anonymous"></script>
</head>
<body>

    <div class="container">
        <nav class="nav">
            <ul class="nav_menu">
                <li>
                    <a href="#">Vaccination.</a>
                 </li>
                 <li>
                    <a href="#">Database.</a>
                 </li>
                 <li>
                    <a href="#">Education.</a>
                 </li>
                 <li>
                    <a href="#">News.</a>
                 </li>
                 <li>
                    <a href="#">Regulation.</a>
                 </li>
                 <li>
                    <a href="#">Hoax Buster.</a>
                 </li>
            </ul>
        </nav>
    </div>

    <h1>Combate Virus Con Vacunas.</h1>

    <div class="contenedor">
        <img src="./Médico.png" alt="medico"/>

        <h2>Let's stop this pandemic by killing the virus
            with a vaccine, don't let yourself and your
            family get infected. </h2>
    </div>
    <br>

    <h3>Schedule your vaccinations.</h3>
    <section class="module">
       <div class="mod_sec">
          <label for="Input1"> Location:</label>
          <br>
          <input type="text" id="Input1" name="Input1">
       </div>
       
       <div>
          <label for="fecha1">Date:</label>
          <input type="date" id="fecha1" name="fecha1">
          <input type="submit">
          <input type="reset">
       </div>
 
       <div>
          <label for="Vaccines">Vaccine type:</label><br><br>
          <select id="Vaccines" name="Vaccines">
              <option value="Moderna.">Moderna</option>
              <option value="AztraZeneka.">AztraZeneka</option>
              <option value="Pfizer.">Pfizer</option>
              <option value="Janssen.">Janssen</option>
              <option value="Sputnik.">Sputnik</option>
              <option value="Cansino.">Cansino</option>
              <option value="Janssen.">Janssen</option>
          </select>
       </div>
       
       <div>
          <form>
             <input type="submit" name="boton" value="Submit">
          </form>
       </div>
    </section>
    <br>
    <h3>Why should I vaccine?</h3>
    <p>In order to avoid any doubts getting the COVID-19 vaccine,<br>
     identify the following 4 beneffits of COVID-19 <br>
     vaccination:</p>

     <section class="column">
        <div class="column1">
           <h4>Minimize the spread of viruses:</h4>
           <p>Vaccine has been proven<br>
           effective to prevent someone<br>
           from getting infected with<br> 
           Coronavirus.</p>
        </div>
        <div>
           <h4>Forming antibodies:</h4>
           <p>COVID-19 vaccine proven to help<br>
           shape antibody response for immune system.</p>
        </div>
        <div>
           <h4>Protecting people nearby:</h4>
           <p>The benefits of COVID-19<br>
           vaccination are the vaccine<br>
           that we get can also help<br>
           protect people around us.</p>
        </div>
        <div>
           <h4>Creating group immunity:</h4>
           <p>COVID-19 vaccination is also<br>
           beneficial for creating group<br>
           immunity or herd immunity.</p>
        </div>
     </section>

    <br>

    <h2>Preparations Before Vaccine.</h2>

    <div class="contenedor1">
        <img src="vacuna.jpg" alt="vacuna"/>
        <p>The success of vaccines is strongly influenced by the<br>
            strength of the body's immune system. Therefore, there are<br>
            several things that can be tried to make the COVID-19<br>
            vaccine work:<br>
            <br>
            1.-Avoid alcoholic beverages.<br>
            <br>
            2.-Avoid stress: Stress as a profound affect on immune work.<br>
            Moreover, prolonged stress can increase cortisol<br>
            production and oxidative stress in the body.<br>
            <br>
            3.-Eat healthy food.<br>
            <br>
            4.-Get enough sleep.<br>
            <br>
            5.-Exercise or physical activity.</p>
    </div>
    <br>
    <h2>Emergency contact.</h2>
    <p>Contact one of the contacts below if you or your family feel<br>
    unwell and have similar symptoms such as Covid-19, make<br>
    sure you also take care of yourself before reporting to us:</p>
    <section class="contacto">
        <div class="links">
           <a href="#">Call: 021.123.145.14.
              <i class="fa-solid fa-phone-volume"></i>
           </a>
           <a href="#">Chat: 021.123.145.14.
              <i class="fa-brands fa-rocketchat"></i>
           </a>
           <a href="#">Video call: 021.123.145.14.
              <i class="fa-solid fa-video"></i>
           </a>
           <a href="#">Message: 021.123.145.14.
              <i class="fa-solid fa-message"></i>
           </a>
        </div>
  
        <div>
           <img class="llama" src="contact.jpg" alt="contacto">
        </div>
        
    </section>

    <br>
    <br>
    <h4>Vaccination:</h4>
    <p>Our goal is to help the
    world free from the
    ongoing pandemic.</p>
    <div class="link_fuera">
       <div class="fuera">
          <ul class="dentro">
             <li>
                <a href="#">
                   <h3>About</h3>
                   <p>About us.<br>
                   Features.<br>
                   New & Blog.<br></p>
                </a>
             </li>
             <li>
                <a href="#">
                   <h3>Company.</h3>
                   <p>How we work?<br>
                   Capital<br>
                   Security</p>
                </a>
             </li>
             <li>
                <a href="#">
                   <h3>Support.</h3>
                   <p>FAQs<br>
                   Support center <br>
                   Contact Us</p>
                </a>
             </li>
          </ul>
       </div>
    </div>
    <br>
    <footer class="footer">
        <div>
            <h5>@2021 Vaccination. All rights reserved.</h5> 
        </div> 
        <div>
            <h5> Terms & Agreements.</h5>
        </div>
        <div>
            <h5>Privacy policy.</h5>
        </div>
     </footer>
</body>
</html>

/*Aquí inicia CSS.*/
*{
    font-family: Arial, Helvetica, sans-serif; 
}

body{
    background-color: #fff;
}

.container{
    width: 90%;
    margin: auto;
}

.nav{
    font-size: 17px;
    display: flex;
    justify-content: right;
    align-items: center;
    height: 120px;
    padding: 20px;
}

.nav_menu{
    display: flex;
    margin: 5px;
    padding: 40px;
    text-align: left;
    text-decoration: none;
}

li a{
    text-decoration: none;
}

 li a:hover{
    background: blue;
    transition: -8s;
    border-radius: 01rem;
}

.nav_menu li{
    padding: 10px;
    list-style: none;
}

h1{
    text-align:center;
    color: blue;
}

h4{
    text-align: left;
    color: blue;
}

.contenedor{
    margin-top: 70px;
    display: flex;
    background-color: grey;
    padding: 25px;
    color: #fff;

}

.contenedor h2{
    margin: auto;
    padding: 10px;
    align-items: center;
    text-align: justify;
}

.module{
    display: grid;
    grid-template-columns: repeat(4,1fr);
    color: blue;
}

.mod_sec{
    padding: 5px;
}

.contenedor1{
    margin-top: 70px;
    display: flex;
    background-color: grey;
    padding: 25px;
    color: #fff;
}

.contenedor1 img{
    width: 300px;
    height: 300px;
}

.column,
.contenedor1 p{
    padding: 5px;
    margin: auto;
    text-align: center;
}

.contenedor3{
    min-height: 50px;
    background-color:azure;
    display: flex;
    justify-content: space-around;
    align-items: center;
    flex-wrap: wrap;
}

.column{
    display: grid;
    grid-template-columns: repeat(4,1fr);
    color: blue;
}

.column1{
    padding: 5px;
    text-align: left;
}

.contenedor5{
    min-height: 50px;
    background-color:azure;
    display: flex;
    justify-content: space-around;
    align-items: center;
    flex-wrap: wrap;
}

h2{
    color: blue;
    text-align: center;
}

h3{
    color: blue;
}

p{
    color: blue;
    
}

.contacto{
    display: grid;
    grid-template-columns: repeat(2,1fr);
    color: blue;
    padding-bottom: 10px;
}

.links{
    display: grid;
    grid-template-columns: repeat(2,1fr);
    padding: 20px;
    padding-bottom: 10px;
}

.llama{
    width: 400px;
    height: 400px;
}

.fuera,
.dentro{
    display: grid;
    grid-template-columns: repeat(3,1fr);
    color: blue;
    list-style: none;
    align-items: center;
    gap: 500px;
}

.dentro li{
    margin: auto;
    line-height: 1.8;
    
}

.footer{
    text-align: center;
    padding: 10px 0;
    background: #2f3640;
    color: #616161;
    font-size: 15px;
    padding-bottom: 20px;
}

@media(max-width: 700px) {
    body{
        background-color: aquamarine;
    }

    .container{
        width: 90%;
        margin: auto;
    }

    .nav{
        font-size: 17px;
        display: flex;
        flex-wrap: wrap;
        justify-content: center;
        align-items: center;
    }

    .nav_menu{
        display: flex;
        flex-wrap: wrap;
        text-align: center;
        font-size: 17px;
    }

    .contenedor{
        width: 90%;
        height: 250px;
        margin-top: 70px;
        display: flex;
        flex: content;
        background-color: grey;
        padding: 25px;
        color: #fff;
    }

    .contenedor1 img{
        width: 150px;
        height: 150px;
    }

    .contenedor h2{
        width: 50%;
        font-size: 20px;
        align-items: center;
        text-align: left;
        justify-content: center;
        padding-left: 100px;
        padding-bottom: 30px;
    }

    .column{
        display: grid;
        grid-template-columns: repeat(2,1fr);
        color: blue;
    }
    
    .column1{
        padding: 5px;
        text-align: left;
    }

    .column1 p{
        font-size: 15px;
        text-align: left;
        justify-content: center;
        align-items: center;

    }
    
    .contenedor1{
        width: 90%;
        height: 380px;
        display: flex;
        background-color: grey;
        padding: 25px;
        padding-bottom: 40px;
        color: #fff;
    }
    
    .contenedor1 img{
        width: 150px;
        height: 150px;
        padding-top: 55px;
    }

    .contacto{
        color: blue;
        padding-bottom: 10px;
    }
    
    .links{
        display: grid;
        grid-template-columns: repeat(1,1fr);
        padding: 20px;
        padding-bottom: 10px;
    }

    
    .llama{
        width: 200px;
        height: 200px;
    }

    .fuera,
    .dentro{
        display: grid;
        grid-template-columns: repeat(3,1fr);
        color: blue;
        list-style: none;
        align-items: center;
        gap: 160px;
    }

    .footer{
        text-align: center;
        padding: 10px 0;
        background: #2f3640;
        color: #616161;
        font-size: 14px;
        padding-bottom: 20px;
    }

    
}

@media(max-width: 400px) {
    body{
        background-color: azure;
    }

    .container{
        margin: auto;
    }

    .nav{
        font-size: 15px;
        justify-content: center;
        align-items: center;
    }

    .nav_menu{
        display: grid;
        grid-template-columns: repeat(3, 1fr);
        text-align: center;
        font-size: 17px;
    }

    h1{
        text-align:center;
        color: blue;
        font-size: 20px;
        margin-left: 13px;
        margin-top: 10px;
        padding-top: 10px;
    }

    .contenedor{
        width: 90%;
        height: 100px;
        margin-top: 70px;
        display: flex;
        flex: auto;
        background-color: grey;
        padding-left: 10px;
        color: #fff;
    }

    .contenedor1 img{
        width: 110px;
        height: 110px;
        align-items: center;
        justify-content: center;
    }

    .contenedor h2{
        width: 100%;
        font-size: 15px;
        align-items: center;
        text-align: center;
        justify-content: center;
        padding-left: 70px;
        padding-bottom: 200px;
        margin: auto;
    }

    h3{
        font-size: 17px;
    }

    p{
        font-size: 15px;
        justify-content: center;
        text-align: left;
    }

    .module{
        font-size: 15px;
        display: flex;
        flex-wrap: wrap;
        line-height: 1;
    }

    .column{
        display: grid;
        grid-template-columns: repeat(2,1fr);
        color: blue;
    }
    
    .column1{
        padding: 5px;
        text-align: left;
    }

    h2{
        font-size: 20px;
    }

    .column1 p{
        font-size: 15px;
        text-align: left;
        justify-content: center;
        align-items: center;

    }
    
    .contenedor1{
        width: 90%;
        height: 290px;
        display: flex;
        background-color: grey;
        padding: 25px;
        padding-bottom: 40px;
        color: #fff;
    }
    
    .contenedor1 img{
        width: 100px;
        height: 100px;
    }

    .contenedor1 p{
        font-size: 12px;
        padding-left: 10px;
    }

    .contacto{
        color: blue;
        padding-bottom: 10px;
    }
    
    .links{
        display: grid;
        grid-template-columns: repeat(1,1fr);
        padding: 20px;
        padding-bottom: 10px;
        line-height: 1.3;
    }

    .llama{
        width: 150px;
        height: 150px;
        padding-top: 15px;
    }

    .fuera,
    .dentro{
        display: grid;
        grid-template-columns: repeat(3,1fr);
        color: blue;
        list-style: none;
        align-items: center;
        gap: 28px;
    }

    .footer{
        text-align: center;
        padding: 10px 0;
        background: #2f3640;
        color: #616161;
        font-size: 13px;
        padding-bottom: 20px;
    }
}
