<template>
    <div>
        <h1 id="about">ABOUT ME</h1>
        <div class="about">
            <p>I am a recent full stack web developer graduate from Life Choices Academy coding boot camp seeking a position as
                a web developer intern. One of my academic achievements includes completing my final project successfully which
                improved my problem-solving skills, time management skills and adaptation to new learning environment. I am in
                pursuit for an environment within which I can broaden my knowledge and grow as a web developer.
            </p>
        </div>

        <div class="personal">
            <img src="https://i.postimg.cc/bN5Rz0T8/GIFT-removebg-preview.png" alt="Gift Profile">
            <div class="text">
                <h3>PERSONAL DETAILS</h3>
                    <p>FULL NAME: Gift Mahlangu</p>
                    <p>DATE OF BIRTH: 1997-03-11</p>
                    <p>GENDER: MALE</p>
                    <p>ADDRESS: Kenwyn, Cape Town</p>
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

.about{
    width: 80rem;
    margin: auto;
    margin-bottom: 1rem;
}
</style>