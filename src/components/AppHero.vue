<script>
import AppTitle from './AppTitle.vue';

export default {
    name: 'AppHero',
    components: { AppTitle }
}

</script>


<template>
    <div class="container">
        <div class="left">
            <p>Lorem ipsum dolor sit amet consectetur adipisicing elit. Assumenda amet maiores possimus nulla illum quas
                cumque
                aliquam, ipsum error saepe quibusdam dolore nisi, voluptatum animi minus esse! Architecto, voluptates
                animi.
            </p>
            <div>

            </div>
            <button href="#">Esplora</button>

        </div>

        <div class="right">
            <AppTitle></AppTitle>

        </div>

    </div>
</template>

<style>
* {
    box-sizing: border-box;
    margin: 0;
    padding: 0;

}

.container {
    display: flex;
    padding: 2em;

    max-width: 800px;
    height: 400px;
    margin-inline: auto;
    background-image: url(../assets/img/1001-800x500.jpg);
    background-size: cover;

}

.right {
    display: flex;
    justify-content: end;
    width: 60%;

}

.left {
    width: 40%;
    padding: 1em;
    border-radius: 20px;
    background-color: rgba(0, 0, 0, 0.4);
    color: white;
}

.left p {
    margin-bottom: 1.5em;
}

.left button {
    text-decoration: none;
    padding: 8px;
    border: 1px solid black;
    border-radius: 10px;

    background-color: #344955;
    color: white;
    box-shadow: rgba(0, 0, 0, 0.3) 1.95px 1.95px 2.6px;

    cursor: pointer;

}

.left button:hover {
    transform: scale(1.1);
}
</style>