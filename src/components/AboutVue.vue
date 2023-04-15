<template>
    <div>
        <h1 id="about">ABOUT ME</h1>
        <!-- <div class="container"> -->
        <p>I am a recent full stack web developer graduate from Life Choices Academy coding bootcamp seeking a position as
            a web developer intern. One of my academic achievements includes completing my final project successfully which
            improved my problem-solving skills, time management skills and adaptation to new learning environment. I am in
            pursuit for an environment within which I can broaden my knowledge and grow as a web developer.</p>
        <!-- </div> -->

        <div class="personal">
            <img src="https://i.postimg.cc/bN5Rz0T8/GIFT-removebg-preview.png" alt="Gift Profile">
            <div class="text">
                <h3>PERSONAL DETAILS</h3>
                <p>Full Name : Gift Mahlangu</p>
                <p>Date Of Birth : 1997-03-11</p>
                <p>Gender : Male</p>
                <p>Address : Kenwyn, Cape Town</p>
            </div>
        </div>
    </div>
</template>

<script>
export default {
    name: "AboutVue"
}
</script>

<style scoped>
.personal {
    display: grid;
    grid-template-columns: repeat(2, 1fr);
}

.text {
    margin-right: 13rem;
    margin-top: 8rem;
    text-align: left;
}

ul {
    color: white;
}

h1 {
    color: #85CDFD;
    margin-top: 6rem;
}

h3 {
    color: #85CDFD;
}

img {
    width: 25rem;
    margin-left: 5rem;
}

.text p {
    margin-top: 1.5rem;
}

.container {
    width: 80rem;
    margin: auto;
    margin-bottom: 1rem;
}

@media screen and (max-width: 900px) {
    .personal {
        display: grid;
        grid-template-columns: 1fr;
        margin: auto;
    }

    img {
        margin: auto;
        margin-left: 18rem;
    }

    .text {
        margin: auto;
        margin-top: 2rem;
    }
}

@media screen and (max-width: 790px) {
    .personal {
        display: grid;
        grid-template-columns: 1fr;
        margin: auto;
    }

    img {
        margin: auto;
        margin-left: 14rem;
    }

    .text {
        margin: auto;
        margin-top: 2rem;
    }
}

@media screen and (max-width: 690px) {
    .personal {
        display: grid;
        grid-template-columns: 1fr;
        margin: auto;
    }

    img {
        margin: auto;
        margin-left: 14rem;
        margin-bottom: 2rem;
    }

    .text {
        margin: auto;
        margin-top: 2rem;
    }
}

@media screen and (max-width: 630px) {
    .personal {
        display: grid;
        grid-template-columns: 1fr;
        margin: auto;
    }

    .text {
        margin: auto;
    }

    img {
        width: 25rem;
        margin: auto;
        margin-left: 10rem;
        margin-bottom: 2rem;
    }

}

@media screen and (max-width: 580px) {

    .personal {
        display: grid;
        grid-template-columns: 1fr;
        margin: auto;
    }

    .container {
        width: 60rem;
        margin: auto;
        margin-bottom: 1rem;
    }

    img {
        width: 25rem;
        margin: auto;
        margin-left: 7rem;
        margin-bottom: 2rem;
    }


}

@media screen and (max-width: 515px) {

    .personal {
        display: grid;
        grid-template-columns: 1fr;
        margin: auto;
    }

    .container {
        width: 50rem;
        margin: auto;
        margin-bottom: 1rem;
    }

    img {
        width: 25rem;
        margin-bottom: 2rem;
        margin-left: 7rem;
        width: 20rem;
    }

}

@media screen and (max-width: 480px) {

    .personal {
        display: grid;
        grid-template-columns: 1fr;
        margin: auto;
    }

    .container {
        width: 50rem;
        margin: auto;
        margin-bottom: 1rem;
    }

    img {
        width: 25rem;
        margin-bottom: 2rem;
        margin-left: 7rem;
        width: 20rem;
    }

}

@media screen and (max-width: 433px) {

    .personal {
        display: grid;
        grid-template-columns: 1fr;
        margin: auto;
    }

    .container {
        width: 50rem;
        margin: auto;
        margin-bottom: 1rem;
    }

    img {
        margin-bottom: 2rem;
        margin-left: 6rem;
        width: 18rem;
    }

}

@media screen and (max-width: 433px) {

    .personal {
        display: grid;
        grid-template-columns: 1fr;
        margin: auto;
    }

    .container {
        width: 50rem;
        margin: auto;
        margin-bottom: 1rem;
    }

    img {
        margin-bottom: 2rem;
        margin-left: 6rem;
        width: 18rem;
    }

}

@media screen and (max-width: 384px) {

    .personal {
        display: grid;
        grid-template-columns: 1fr;
        margin: auto;
    }

    .container {
        width: 50rem;
        margin: auto;
        margin-bottom: 1rem;
    }

    img {
        margin-left: 6rem;
        width: 14rem;
        margin-bottom: 2rem;
    }

    h3 {
        color: #85CDFD;
        font-size: 1.3rem;
    }

}

@media screen and (max-width: 384px) {

    .personal {
        display: grid;
        grid-template-columns: 1fr;
        margin: auto;
    }

    .container {
        width: 50rem;
        margin: auto;
        margin-bottom: 1rem;
    }

    img {
        /* margin: auto; */
        margin-left: 3rem;
        width: 14rem;
        margin-bottom: 2rem;
    }

    h3 {
        color: #85CDFD;
        font-size: 1.3rem;
    }

}</style>