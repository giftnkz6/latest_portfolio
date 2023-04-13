<template>
    <div class="resume">
        <h1 id="resume">RESUME</h1>
        <div class="container">
            <div class="row">
                <div class="col-md-12">
                    <div class="container">
                        <div class="resume-timeline">
                            <a href="" class="info">

                                <h3 class="year">2018-2021</h3>
                                <p class="description">
                                    Lorem ipsum dolor sit amet, consectetur adipiscing elit. Integer males uada tellus
                                    lorem, et condimentum neque commodo Integer males uada tellus lorem, et condimentum
                                    neque commodo
                                </p>
                            </a>
                        </div>
                        <div class="resume-timeline">
                            <div class="info">

                                <h3 class="year">2013-2017</h3>
                                <p class="description">
                                    Lorem ipsum dolor sit amet, consectetur adipiscing elit. Integer males uada tellus
                                    lorem, et condimentum neque commodo Integer males uada tellus lorem, et condimentum
                                    neque commodo
                                </p>
                            </div>
                        </div>
                        <div class="resume-timeline">
                            <div class="info">

                                <h3 class="year">2009-2012</h3>
                                <p class="description">
                                    Lorem ipsum dolor sit amet, consectetur adipiscing elit. Integer males uada tellus
                                    lorem, et condimentum neque commodo Integer males uada tellus lorem, et condimentum
                                    neque commodo
                                </p>
                            </div>
                        </div>
                        <div class="resume-timeline">
                            <div class="info">

                                <h3 class="year">2006-2009</h3>
                                <p class="description">
                                    Lorem ipsum dolor sit amet, consectetur adipiscing elit. Integer males uada tellus
                                    lorem, et condimentum neque commodo Integer males uada tellus lorem, et condimentum
                                    neque commodo
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

/* body {
    margin-top: 100px !important;
} */

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

a {
    text-decoration: none;
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
    color: #777;
    font-size: 13px;
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

/* .container .resume-timeline:nth-child(even) .info {
    border-radius: 15px 15px 15px 0;
}

.container .resume-timeline:nth-child(4n+2):before,
.container .resume-timeline:nth-child(4n+2):after {
    border-color: #ff70a6;
}

.container .resume-timeline:nth-child(4n+2) .info {
    background: #ff70a6;
}

.container .resume-timeline:nth-child(4n+3):before,
.container .resume-timeline:nth-child(4n+3):after {
    border-color: #ff9770;
} */

/* .container .resume-timeline:nth-child(4n+3) .info {
    background: #ff9770;
}

.container .resume-timeline:nth-child(4n+4):before,
.container .resume-timeline:nth-child(4n+4):after {
    border-color: #ffd670;
}

.container .resume-timeline:nth-child(4n+4) .info {
    background: #ffd670;
} */

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

    /* .container .info,
    .container .resume-timeline:nth-child(even) .info {
        border-radius: 0 15px 15px 15px;
    } */
}
</style>