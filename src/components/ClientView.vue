<template>
    <div class="client-container">
        <p class="bold">Our Clients</p>
        <div class="client-wrapper">
            <img class="client-img" src="../assets/apple-logo.webp" alt="">
            <img class="client-img" src="../assets/adidas-logo.jpeg" alt="">
            <img class="client-img" src="../assets/chanel-logo.png" alt="">
            <img class="client-img" src="../assets/nokia-logo.jpg" alt="">
            <img class="client-img" src="../assets/nike-logo.webp" alt="">
            <img class="client-img" src="../assets/mcdo-logo.png" alt="">
        </div>
    </div>
</template>


<style scoped>
@import url('https://fonts.googleapis.com/css2?family=Roboto:wght@400;700&display=swap');
.client-wrapper {
    display: flex;
    flex-wrap: wrap;
    justify-content: space-around;
}

.client-container {
    text-align: center;
    font-family: 'Roboto', sans-serif;
    padding-top:5% ;padding-bottom: 5%;
}

.bold {
    font-weight: 700;
    font-size: 2em;
}

.client-img {
    height: 35dvh;
    width: 30dvw;
}

</style>