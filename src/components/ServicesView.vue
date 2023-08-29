<template>
    <div class="serv-container">
        <p class="big bold" id="services">Our Services</p>

        <div class="serv-wrapper">

            <div class="serv-card">
                <img class="serv-img" src="../assets/serv1.webp" alt="">
                <p class="bold">Web Design and Development</p>
                <p>Creating beautiful and functional websites that reflect your <br>brand and meet your business needs.</p>
                <div class="serv-btn-container">
                    <button class="serv-btn">More info</button>
                </div>
            </div>

            
            <div class="serv-card">
                <img class="serv-img" src="../assets/serv2.webp" alt="">
                <p class="bold">e-Commerce Websites</p>
                <p>Designing and developing custom e-commerce solutions <br>that help you sell your products and services online.</p>
                <div class="serv-btn-container">
                    <button class="serv-btn">More info</button>
                </div>
            </div>

            
            <div class="serv-card">
                <img class="serv-img" src="../assets/serv3.webp" alt="">
                <p class="bold">Website maintenance</p>
                <p>Providing regular updates and support to keep your <br>website running smoothly and ensure maximum uptime and security</p>
                <div class="serv-btn-container">
                    <button class="serv-btn">More info</button>
                </div>
            </div>

        </div>

    </div>

</template>


<style scoped>
@import url('https://fonts.googleapis.com/css2?family=Roboto:wght@400;700&display=swap');

#services {
    text-align: center;
}
.serv-container {
    color: white;
    background-color:#6247AA;
    font-family: 'Roboto', sans-serif;
    padding-top: 3%; padding-bottom: 3%;
}

.serv-wrapper {
    background-color: #6247AA;
    color: white;
    display: flex;
    justify-content: space-around;
}

.serv-img {
    border-radius: 18px;
    height: 40dvh;
    width: 25dvw;
}

.bold {
    font-weight: 700;
    font-size: 1.25em;
}

.big {
    font-size: 2.5em;
}

.serv-btn {
    background-color: #E2CFEA;
    width: fit-content;
    border: none;
    border-radius: 15px;
    padding: 2%;
    color: white;
    font-size: 1.25em;
}

</style>