<template>
    <div class="description-container">

        <img class="desc-img" src="../assets/description-img.jpg" alt="">

        <div class="desc-wrapper">
        <p class="bold">About us</p>
        <p class="description-text">
            Webby is a leading web development agency based in Abidjan, 
            Côte divoire. <br>With a team of highly skilled professionals, 
            we specialize in creating cutting-<br>edge websites that are visually stunning and functionally robust. 
            Our goal is to <br>help businesses establish a strong online presence and achieve their digital <br>objectives. 
            Whether you need a simple website or a complex e-commerce <br>platform,
            we have the expertise to deliver customized solutions that meet your <br>specific requirements. 
            At Webby, we are committed to providing exceptional 
            <br>web development services that drive growth and success for our clients.
        </p>
        <div class="desc-btn-container">
        <button class="desc-btn">Contact</button>
    </div>
    </div>
        
    </div>
</template>


<style scoped>
@import url('https://fonts.googleapis.com/css2?family=Roboto:wght@400;700&display=swap');

.description-container {
    font-family: 'Roboto', sans-serif;
    display: flex;
    justify-content: space-around;
    padding: 8%;
}

.desc-wrapper {
    display: flex;
    flex-direction: column;

}

.desc-img {
    border-radius: 18px;
}

.bold {
    font-weight: 700;
    font-size: 2em;
}

.desc-btn {
    background-color: #E2CFEA;
    width: fit-content;
    border: none;
    border-radius: 15px;
    padding: 2%;
    color: white;
    font-size: 1.25em;
}

@media screen and (max-width: 1000px) {
    .description-container {
        display: flex;
        flex-direction: column;
    }
    .desc-img {
        height: 20vh;
    }
}

</style>