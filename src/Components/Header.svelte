<script>
let Logo = 'https://huddle-challenge-git-main.david1012.vercel.app/images/logo.svg'

let styles = { darkMode: false }

function toggle () {
    styles.darkMode = !styles.darkMode
    window.document.body.classList.toggle("dark-mode")
}

</script>

<style>

:global(body.dark-mode) header {
	color: white;
}

header {
    display: flex;
    justify-content: space-between;
    margin: 20px 70px 30px 70px;
}

header a img {
    width: 200px;
}

header button {
    color: hsl(322, 100%, 66%);
    text-decoration: none;
    padding: 8px 35px;
    border: 2px solid hsl(322, 100%, 66%) ;
    border-radius: 50px;
    background-color: transparent;
}

header button:hover {
    background-color: hsl(321, 100%, 78%);
    border: 2px solid hsl(321, 100%, 78%);
    color: white;
    cursor: pointer;
}

@media (max-width: 1000px) {

    header{
        margin-left: 5px;
        margin-right: 5px;
    }
}

</style>

<header>
    <a href="platzi.com">
      <img src={Logo} alt="Logo Huddle">
    </a>
    <button on:click={toggle}>
        Dark Mode
    </button>
  </header>
