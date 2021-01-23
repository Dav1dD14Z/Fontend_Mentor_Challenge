<script>
    let logo = 'https://huddle-page-opal.vercel.app/images/logoc.svg'
    let phone = 'https://huddle-challenge-git-main.david1012.vercel.app/images/icon-phone.svg'
    let email = 'https://huddle-challenge-git-main.david1012.vercel.app/images/icon-email.svg'
</script>

<style>

footer {
    width: 100%;
    height: 350px;
    background-color: hsl(192, 100%, 9%);
    color: white;
}

.footer-container {
    max-width: 1000px;
    margin: 0 auto;
    position: relative;
}

.footer-container .info {
    position: absolute;
    left: 0;
    margin-top: 50px;
    width: 40%;
}

.newsletter {
    position: absolute;
    right: 0;
    margin-top: 50px;
    width: 40%;
}

input {
    width: 60%;
    background-color: white;
    border: 1px solid white;
    outline: none;
    height: 35px;
    border-radius: 5px;
    margin-bottom: 20px;
    color: black;
    margin-right: 7px;
}

button {
    width: 35%;
    margin-bottom: 20px;
    background-color: hsl(322, 100%, 66%);
    border: 1px solid hsl(322, 100%, 66%);
    outline: none;
    height: 35px;
    border-radius: 5px;
    color: white;
}

button:hover {
    cursor: pointer;
    background-color: transparent;
    color: hsl(322, 100%, 66%);
}

@media (max-width: 1000px) {

    footer {
        height: 450px;
        position: relative;
    }

    .footer-container {
        width: 100%;
    }
    
    .footer-container .info {
        position: absolute;
        top: 0;
        left: 0;
        right: 0;
        margin-top: 250px;
        width: 100%;
    }
    
    .newsletter {
        position: absolute;
        top: 0;
        right: 0;
        margin-top: 0px;
        width: 100%;
    }


}

</style>

<footer class="footer">
    <div class="footer-container">
        <div class="info">
            <img src={logo} alt="">
            <p>Lorem ipsum dolor sit amet, consectetur
                adipiscing elit. Mauris nulla quam, hendrerit
                lacinia vestibulum a, ultrices quis sem.
            </p>
            <p>
                <img src={phone} alt=""> 
                Phone: +1-543-123-4567
            </p>
            <p>
                <img src={email} alt=""> 
                example@huddle.com
            </p>
        </div>
        <div class="newsletter">
            <h2>NEWSLETTER</h2>
            <p>
                To recieve tips on how to grow your community,
                sign up to our weekly newsletter. We’ll never send
                you spam or pass on your email address.
            </p>
            <input type="text" placeholder="Send..">
            <button>Send</button>
        </div>
    </div>
</footer>