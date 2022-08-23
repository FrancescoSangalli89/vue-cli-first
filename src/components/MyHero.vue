<template>
    <div class="jumbotron">
        <img class="jumbotronImage" src="https://upload.wikimedia.org/wikipedia/commons/thumb/9/9f/Oracle_Arena_JumboTron.JPG/1200px-Oracle_Arena_JumboTron.JPG" alt="Jumbotron Image">
        <a class="link" href="https://en.wikipedia.org/wiki/Jumbotron" target="_blank">Sig e Sig.re ecco a voi il Jumbotron..</a>
    </div>
</template>

<script>
    export default {
        name: "MyHero"
}
</script>

<style>
    .jumbotron{
        position: relative;
    }
    .jumbotronImage {
        width: 100%;
        height: calc(100vh - 119.5px);
    }
    .link {
        text-decoration: none;
        color: rgb(199, 191, 191);
        position: absolute;
        bottom: 10%;
        left: 5%;
        font-size: 3rem;
        font-weight: bold;
        width: 20%;
    }
</style>