<script></script>

<template>

    <div class="jumbotron d-flex">
        <h2 class="text">Jumbotron con Vite!</h2>
        <p class="text">Lorem ipsum dolor sit, amet consectetur adipisicing elit. Maxime, perferendis aperiam hic rerum
            error laborum nihil animi veritatis non optio iusto numquam nostrum deleniti dicta tempora saepe.
            Blanditiis, accusamus omnis?</p>
        <button class="btn">Click me</button>
    </div>


</template>

<style scoped>
.jumbotron {
    height: 600px;
    max-width: 80%;
    background-image: url('../assets/img/jumbo.webp');
    background-size: cover;
}

.jumbotron text {
    text-align: center;
}

.btn {
    border-radius: 25%;
    background-color: blue;
}

.d-flex {
    display: flex;
    justify-content: center;
    align-items: center;
    flex-direction: column;
}
</style>