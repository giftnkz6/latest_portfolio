<template>
    <div class="resume">
        <h1 id="resume">RESUME</h1>
        <div class="container">
            <div class="row">
                <div class="col-md-12">
                    <div class="container">
                        <div class="resume-timeline">
                            <div class="info">

                                <h3 class="year">2023-Present</h3>
                                <p class="description">
                                    Intern Web Developer intern at LC Studio based in Kenwyn, Cape Town. Focussed on upskilling and working in teams to achieve the same goals.
                                    It is a work simulated environment teaching soft and technical skills.
                                </p>
                            </div>
                        </div>
                        <div class="resume-timeline">
                            <div class="info">

                                <h3 class="year">2022-2023</h3>
                                <p class="description">
                                    I completed a 6 months full stack web development bootcamp at Life Choices Coding Academy. I finished in the top 4 excellent achievers in my class with an average of 88%.
                                    I learned HTML, CSS, JAVASCRIPT, BOOTSTRAP, VUEJS, NODEJS, MYSQL and midfullness.
                                </p>
                            </div>
                        </div>
                        <div class="resume-timeline">
                            <div class="info">

                                <h3 class="year">2022</h3>
                                <p class="description">
                                    On 16 April 2022 I got a Responsive Web Design certificate from FreeCodeCamp Which covers HTML, CSS, Web design and Responsive Web design.
                                </p>
                            </div>
                        </div>
                        <div class="resume-timeline">
                            <div class="info">

                                <h3 class="year">2017-2020</h3>
                                <p class="description">
                                    In 2017 I was enrolled for a Bsc in Computer Sciences at University Of Pretoria. I partially completed the degree due to some unforseen circurmstances and financial challenges.
                                </p>
                            </div>
                        </div>

                        <div class="resume-timeline">
                            <div class="info">

                                <h3 class="year">2013-2015</h3>
                                <p class="description">
                                    In 2015 I obtained my matric certificate at Kwandebele Science Combined School. I achieved a bachelors pass, with Pure Mathematics and Sciences beign one of the passed subjects.
                                </p>
                            </div>
                        </div>
                    </div>
                </div>
            </div>
        </div>
    </div>
</template>

<script>
export default {
    name: "ResumeVue"
}
</script>

<style scoped>
.resume {
    margin-top: 7rem;
}

h1 {
    color: #85CDFD;
    margin-bottom: 2rem;
}

.container {
    font-family: 'Poppins', sans-serif;
}

.container:after {
    content: '';
    display: block;
    clear: both;
}

.container .resume-timeline {
    width: calc(50% + 17px);
    padding: 0 30px 30px 0;
    float: left;
    position: relative;
}

.container .resume-timeline:before,
.container .resume-timeline:after {
    content: '';
    height: 60px;
    width: 2px;
    border-left: 2px solid #70d6ff;
    transform: rotate(-45deg);
    position: absolute;
    right: 30px;
    bottom: 0;
}

.container .resume-timeline:after {
    background-color: #fff;
    height: 20px;
    width: 20px;
    /* border: 6px solid #70d6ff; */
    border-radius: 50%;
    right: 0;
}

.year{
    color: #DEFCF9;
}
.container .info {
    color: #555;
    /* background: #70d6ff; */
    text-align: center;
    min-height: 170px;
    padding: 30px 35px 35px;
    /* border-radius: 15px 15px 0 15px; */
    display: block;
    position: relative;
    z-index: 1;
}

.container .info:before {
    content: '';
    background-color: #85CDFD;
    position: absolute;
    left: 17px;
    right: 17px;
    top: 17px;
    bottom: 17px;
    z-index: -1;
}



.container .year {
    font-size: 22px;
    font-weight: 700;
    letter-spacing: 2px;
    text-transform: uppercase;
    margin: 0 0 8px;
}


.container .description {
    color: white;
    font-size: 18px;
    font-weight: 400;
    letter-spacing: 0.5px;
    line-height: 18px;
    margin: 0;
}

.container .resume-timeline:nth-child(even) {
    padding: 0 0 30px 30px;
    float: right;
}

.container .resume-timeline:nth-child(even):before {
    transform: rotate(45deg);
    right: auto;
    left: 30px;
}

.container .resume-timeline:nth-child(even):after {
    right: auto;
    left: 0;
}


@media screen and (max-width:767px) {
    .container .resume-timeline {
        width: 100%;
        padding: 30px 0 0 30px;
        margin: 0 0 20px;
    }

    .container .resume-timeline:before,
    .container .resume-timeline:nth-child(even):before {
        transform: rotate(-45deg);
        bottom: auto;
        top: 0;
        right: auto;
        left: 30px;
    }

    .container .resume-timeline:after,
    .container .resume-timeline:nth-child(even):after {
        bottom: auto;
        top: 0;
        right: auto;
        left: 0;
    }
}
</style>