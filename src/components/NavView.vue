<template>
    <div class="nav-container">

        <div class="nav-socials">
            <img src="../assets/facebook.png" height="48">
            <img src="../assets/insta.png" height="48">
            <img src="../assets/twitter.png" height="48">
        </div>

        <div class="nav-title">
            <h1>Webby</h1>
        </div>
    </div>
</template>


<style scoped>

@import url('https://fonts.googleapis.com/css2?family=Roboto&display=swap');
.nav-container {
    display: flex;
    justify-content: space-around;
    background-color: #6247AA;
    height:10dvh;
    align-items: center;
}

.nav-socials {
    width: 15dvw;
    display: flex;
    justify-content: space-around;
    filter: invert();
}

.nav-title {
    text-align: center;
    color: white;
    font-size: 1.5em;
    font-family: 'Roboto', sans-serif;
}


</style>