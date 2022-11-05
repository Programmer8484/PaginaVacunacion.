# PaginaVacunacion.
PracticaCSS.

<!DOCTYPE html>
<html lang = "en">
<head>
    <meta charset = "UTF-8">
    <meta http-equiv="X-UA-Compatible" content="IE=edge">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Vacunación.</title>
    <link rel="stylesheet" href="./PagVacunación.css">
    
</head>
<body>
    <h1>Combate Virus Con Vacunas.</h1>

    <div class="contenedor">
        <img src="./Médico.png" alt=""/>

        <h2>Let's stop this pandemic by killing the virus<br>
            with a vaccine, don't let yourself and your<br>
            family get infected. </h2>
    </div>
    <br>
    <h3>Select a vaccine.</h3>
    <label for="Vaccines">Schedule your vaccinations.</label><br><br>
    <select id="Vaccines" name="Vaccines">
        <option value="Moderna.">Moderna</option>
        <option value="AztraZeneka.">AztraZeneka</option>
        <option value="Pfizer.">Pfizer</option>
        <option value="Janssen.">Janssen</option>
        <option value="Sputnik.">Sputnik</option>
        <option value="Cansino.">Cansino</option>
        <option value="Janssen.">Janssen</option>
    </select>
    <br>
    <br>
    <label for="Input1"> Write your location.</label>
    <br>
    <input type="text" id="Input1" name="Input1">
    <br>
    <h3>Select date.</h3>
    <input type="date" id="fecha1" name="fecha1">
    <input type="submit">
    <input type="reset">
    <br>
    <h3>Why should I vaccine?</h3>
    <p>In order to avoid any doubts getting the COVID-19 vaccine,<br>
     identify the following 4 beneffits of COVID-19 <br>
     vaccination:</p>

        <section class="contenedor4">
            <h3>Minimize the spread of viruses:</h3>
            <p>Vaccine has been proven<br>
            effective to prevent someone<br>
            from getting infected with<br> 
            Coronavirus.</p>

            <h3>Forming antibodies:</h3>
            <p>COVID-19 vaccine proven to help<br>
            shape antibody response for immune system.</p>

            <h3>Protecting people nearby:</h3>
            <p>The benefits of COVID-19<br>
            vaccination are the vaccine<br>
            that we get can also help<br>
            protect people around us.</p>

            <h3>Creating group immunity:</h3>
            <p>COVID-19 vaccination is also<br>
            beneficial for creating group<br>
            immunity or herd immunity.</p>
        </section>

    <br>

    <h2>Preparations Before Vaccine.</h2>

    <div class="contenedor1">
        <img src="./Diseño sin título.png" alt=""/>
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
    <h2 class="contact">Emergency contact.</h2>
        <section class="contenedor3">
            <p>Contact one of the contacts below if you
            or your family feel unwell and have similar
            symptoms such as COVID-19, make sure you also
            take care of yourself before reporting to us:
            <br>
            <p>Call: 021.123.145.14</p>
            <br>
            <p>Chat: 021.123.145.14 </p>
            <br>
            <p>Video call: 021.123.145.14</p>
            <br>
            <p>Message: 021.123.145.14</p>
        </section>
    <br>
    <br>
        <section class="contenedor5">
            <h2>Vaccination:</h2>
            <p class="logro">Our goal is to help the<br>
            world free from the<br>
            ongoing pandemic.</p>
            <br>
            <h2 class="about">About:</h2>
            <p>About us<br>
            Features<br>
            New & Blog <br></p>
            <br>
            <h2>Company:</h2>
            <p class="como">How we work?<br>
            Capital<br>
            Security</p>
            <br>
            <h2 class="support">Support:</h2>
            <p class="faq">FAQs<br>
            Support center <br>
            Contact Us</p>
        </section>
    <br>
</body>
</html>

/*Aquí inicia CSS.*/

*{
    font-family: Arial, Helvetica, sans-serif; 
}

body{
    background-color:azure;
}

h1{
    text-align:center;
    color: blue;
}

.contenedor{
    margin-top: 70px;
    display: flex;
    background-color: grey;
    padding: 25px;
    color: #fff;

}

.contenedor1{
    margin-top: 70px;
    display: flex;
    background-color: grey;
    padding: 25px;
    color: #fff;
}

.contenedor3{
    min-height: 50px;
    background-color:azure;
    display: flex;
    justify-content: space-around;
    align-items: center;
    flex-wrap: wrap;
}


.contenedor4{
    min-height: 50px;
    background-color:azure;
    display: flex;
    justify-content: space-around;
    align-items: center;
    flex-wrap: wrap;
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

.contact{
    text-align: left;
}

.logro{
    text-align: center;
}

.about{
    text-align: left;
}

.como{
    text-align: center;
}

.support{
    text-align: right;
}

.faq{
    text-align: right;
}
