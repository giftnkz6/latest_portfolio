<template>
    <h1 id="project">MY PROJECTS</h1>
    <div class="container">
      <div id="carouselExampleControls" class="carousel slide" data-interval="false">
        <div class="carousel-inner">
          <div class="carousel-item active" v-for="project in firstProject" key="project">
            <div class="card">
                <img :src="project.image" class="d-block w-100" alt="..." loading="lazy">
                <div class="card-body">
                    <h5 class="card-title">{{ project.description }}</h5>
                    <a :href="project.github" class="btn" target="_blank">Github</a><br><br>
                    <a :href="project.netlify" class="btn" target="_blank">Netlify</a>
                </div>
            </div>
          </div>
          <div class="carousel-item" v-for="project in projects" key="project">
            <div class="card">
                <img :src="project.image" class="d-block w-100" alt="..." loading="lazy">
                <div class="card-body">
                    <h5 class="card-title">{{ project.description }}</h5>
                    <a :href="project.github" class="btn" target="_blank">Github</a><br><br>
                    <a :href="project.netlify" class="btn" target="_blank">Netlify</a>
                </div>
            </div>
          </div>
        </div>
        <button class="carousel-control-prev" type="button" data-bs-target="#carouselExampleControls" data-bs-slide="prev">
            <span class="carousel-control-prev-icon" aria-hidden="true"></span>
            <span class="visually-hidden">Previous</span>
        </button>
        <button class="carousel-control-next" type="button" data-bs-target="#carouselExampleControls" data-bs-slide="next">
            <span class="carousel-control-next-icon" aria-hidden="true"></span>
            <span class="visually-hidden">Next</span>
        </button>
      </div>
</div>
</template>

<script>
export default {
    name: 'ProjectVue',
    data(){
        return{
            firstProject:[{
                id:1,
                description:"Full Stack Vue E-commerce",
                image:"https://i.postimg.cc/gkGn1X46/Screenshot-1.png",
                github: "https://github.com/giftnkz6/CAPSTONE_FULL_STACK.git",
                netlify: "https://clothinghub-4bc17.web.app"

            }],
            projects:[
            {
                id:2,
                description:"Javascript E-commerce",
                image:"https://i.postimg.cc/G3NksBKn/Screenshot-20230112-101713.png",
                github: "https://github.com/giftnkz6/E-Commerce.git",
                netlify: "https://giftsneakerhub.netlify.app"

            },

            {

                id:3,
                description:"Calculator",
                image:"https://i.postimg.cc/MGm0LR4f/Screenshot-20230112-112156.png",
                github: "https://github.com/giftnkz6/JavaScript-Calculator-.git",
                netlify: "https://calculator-by-gift-mahlangu.netlify.app"
            },
            {
                id:4,
                description:"First Portfolio",
                image:"https://i.postimg.cc/xCHJXbDT/Screenshot-20230112-112412.png",
                github: "https://github.com/giftnkz6/vuePortfolio.git",
                netlify: "https://vueportfolio2023.web.app"
            },
            {
                id:5,
                description:"Counting Characters",
                image:"https://i.postimg.cc/7LqY2jbW/Screenshot-20230113-105901.png",
                github: "https://github.com/giftnkz6/Second-Group-App.git",
                netlify: "https://second-group-app.netlify.app"
            },
            {
                id:6,
                description:"E-commerce-Exercise",
                image:"https://i.postimg.cc/SRKjB3cP/Screenshot-20230113-111903.png",
                github: "https://github.com/giftnkz6/E-commerce-Exercise.git",
                netlify: "https://giftecommerce.netlify.app"
            }
        ]
        }
    }
}
</script>

<style scoped>
    img{
        height: 20rem;
        object-fit: cover;
        object-position: top;
        width: 5rem;
    }

    a{
        background-color:#3C84AB;
        color: white;
    }

    a:hover{
        background-color:#3C84AB;
    }
    .container{
        margin: auto;
    }

    h1{
        margin-top: 3rem;
    }

    h3 {
    color: #85CDFD;
}
    .card{
        margin: auto;
        margin-top: 2rem;
        margin-bottom: 5rem;
        gap: 1rem;
        background-color: #85CDFD;
    }
   
    /* Carousel */
    .carousel-control-next-icon {
        background-image: url("data:image/svg+xml;charset=utf8,%3Csvg xmlns='http://www.w3.org/2000/svg' fill='skyblue' viewBox='0 0 8 8'%3E%3Cpath d='M2.75 0l-1.5 1.5 2.5 2.5-2.5 2.5 1.5 1.5 4-4-4-4z'/%3E%3C/svg%3E");
    }

    .carousel-control-prev-icon {
        background-image: url("data:image/svg+xml;charset=utf8,%3Csvg xmlns='http://www.w3.org/2000/svg' fill='skyblue' viewBox='0 0 8 8'%3E%3Cpath d='M5.25 0l-4 4 4 4 1.5-1.5-2.5-2.5 2.5-2.5-1.5-1.5z'/%3E%3C/svg%3E");
    }

    .card{
        width: 18rem;
    }

    @media screen and (max-width: 400px) {
        .card{
            width: 15rem;
        }
    }

    @media screen and (max-width: 360px) {
        .card{
            width: 13rem;
        }
    }
</style>