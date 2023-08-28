<template>
    <div class="hero-container">
        <p class="hero-text bold">Transform Your Web <br>Presence</p>
        <p class="hero-text">Get a stunning website that showcases your business and <br>attract more customers</p>
        <div class="hero-btn-container">
            <button class="hero-btn">Get Started</button>
        </div>

    </div>
</template>

<style scoped>
@import url('https://fonts.googleapis.com/css2?family=Roboto:wght@400;700&display=swap');

.hero-container {
    background: linear-gradient(rgba(0, 0, 0, 0.5), rgba(0, 0, 0, 0.5)), url('../assets/hero-banner.jpg');
    display: flex;
    justify-content: center;
    flex-direction: column;
    text-align: center;
    padding-bottom: 8%;
}

.hero-text {
    color: white;
    font-family: 'Roboto', sans-serif;
    font-size: 1.5em;
}

.bold {
    font-weight: 700;
    font-size: 3.5em;
}

.hero-btn {
    background-color: #E2CFEA;
    width: fit-content;
    border: none;
    border-radius: 15px;
    padding: 1%;
    color: white;
    font-size: 1.25em;
}

.hero-btn-container {
    display: flex;
    justify-content: center;
}

</style>