<script>
    let logoPrincipal = 'https://huddle-challenge-git-main.david1012.vercel.app/images/screen-mockups.svg'
    let familia = 'https://huddle-challenge-git-main.david1012.vercel.app/images/icon-communities.svg'
    let Message = 'https://huddle-challenge-git-main.david1012.vercel.app/images/icon-messages.svg'

</script>

<style>
.feature {
    display: flex;
    justify-content: center;
}

.feature h2 {
    color: var(--LightDark);
    text-align: center;
    font-size: 50px;
    font-weight: bolder;
    font-family: 'Open Sans', sans-serif;
    margin-bottom: 30px;
}

.feature p {
    text-align: center;
    color: var(--LightDark);
    margin-bottom: 30px;
}

.feature .contenedor-link {
    display: flex;
    justify-content: center;
}

.feature a {
    background-color: hsl(322, 100%, 66%);
    border: 2px solid hsl(322, 100%, 66%);
    color: white;
    padding: 8px 35px;
    border-radius: 50px;
    text-decoration: none;
    margin-bottom: 40px;
}

.feature a:hover {
    color: hsl(322, 100%, 66%);
    text-decoration: none;
    border: 2px solid hsl(322, 100%, 66%) ;
    background-color: transparent;
}

.feature .main {
    width: 100%;
}


/*Tarjetas / Cards*/
.feature .contenedor__info {
    display: flex;
    justify-content: center;
    width: 100%;
}

.feature .contenedor__info-1 {
    margin-right: 150px;
    text-align: left;
}

.feature .contenedor__info-1 h2 {
    text-align: left;
    margin: 0px;
    font-size: 70px;
    font-family: 'Open Sans', sans-serif;
}

.feature .contenedor__info-1 p {
    margin-top: 5px;
    color: var(--LightDark);
    text-align: center;
}

.feature .contenedor__info-1 img {
    width: 30px;
}

.feature .contenedor__info-2 {
    margin-left: 150px;
}

.feature .contenedor__info-2 h2 {
    margin: 0px;
    text-align: left;
    font-size: 70px;
    font-family: 'Open Sans', sans-serif;
}

.feature .contenedor__info-2 p {
    margin-top: 5px;
    color: var(--LightDark);
    text-align: center;
}

.feature .contenedor__info-2 img {
    width: 30px;
}

@media (max-width: 1000px) {

    .feature .contenedor__info {
        display: block;
    }

    .feature .contenedor__info-1 {
        margin-right: 0px;
        margin-top: 100px;
        text-align: center;
    }
    .feature .contenedor__info-1 h2{
        text-align: center;
    }

    .feature .contenedor__info-2 {
        margin-right: 0px;
        margin-left: 0px;
        margin-top: 100px;
        text-align: center;
    }
    .feature .contenedor__info-2 h2{
        text-align: center;
    }

}

</style>

<section class="feature">
    <div class="contenedor">
      <h2>
        Build The Community Your Fans Will Love
      </h2>
      <p>
        Huddle re-imagines the way we build communities. You have a
        <br>
        voice, but so does your audience. Create connections with your
        <br>
        users as you engage in genuine discussion.
      </p>
      <div class="contenedor-link">
        <a href="ss">
          Get Started For Free
        </a>
      </div>
      <img class="main" src={logoPrincipal} alt="Logo Principal">
      <div class="contenedor__info">
        <div class="contenedor__info-1">
          <img src={familia} alt="Logo de comunidad">
          <h2>
            1.4k+
          </h2>
          <p>
            Communities Formed
          </p>
        </div>
        <div class="contenedor__info-2">
          <img src={Message} alt="Logo mensajes">
          <h2>
            2.7m+
          </h2>
          <p>
            Messages Sent
          </p>
        </div>
      </div>
    </div>
</section>