<script>
    export let info;
    export let title;
    export let image;
    export let position_1;
    export let position_2;
    export let text_align;

</script>

<style>

.main {
    max-width: 1000px;
    margin: 300px auto;
}

.main-container {
    position: relative;
    height: 100px;
    width: 100%;
    display: flex;
    align-items: center;
}

.main-container__info,
.main-container__image {
    position: absolute;
}

.main-container__info {
    width: 45%;
}

.main-container__info h2 {
    font-size: 40px;
    color: var(--LightDark);
}

.main-container__info p{
    font-size: 20px;
    color: var(--LightDark);
}

.main-container__image {
    right: 0;
    width: 45%;
}

@media (max-width: 1000px) {

    .main {
        width: 100%;
        margin: 0px;
    }

    .main-container{
        height: 600px;
        display: block;
    }

    .main-container__info {
        width: 100%;
        bottom: 0;
        right: 0;
        left: 0;
        text-align: center;
    }

    .main-container__info h2 {
        text-align: center;
    }

    .main-container__info p{
        text-align: center;
    }   

    .main-container__image {
        top: 0;
        left: 0;
        right: 0;
        width: 100%;
        display: flex;
        justify-content: center;
    }
}



</style>

<section class="main">
    <div class="main-container">
        <div class="main-container__info" style={position_1}>
            <div class="contenedor" style={text_align}>
                <h2>{title}</h2>
                <p>
                    {info}
                </p>
            </div>
        </div>
        <div class="main-container__image" style={position_2}>
            <img src={image} alt="" width="400px">
        </div>
    </div>
</section>