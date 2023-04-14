<template>
    <div>
        <h1 id="skill">MY SKILLS</h1>
        <div class="skills">
            <div>
                <i class="fa-brands fa-html5"></i>
                <p>HTML</p>
            </div>
            <div>
                <i class="fa-brands fa-css3-alt"></i>
                <p>CSS</p>
            </div>
            <div>
                <i class="fa-brands fa-bootstrap"></i>
                <p>BOOTSTRAP</p>
            </div>
            <div>
                <i class="fa-brands fa-square-js"></i>
                <p>JAVASCRIPT</p>
            </div>
            <div>
                <i class="fa-brands fa-vuejs"></i>
                <p>VUEJS</p>
            </div>
            <div>
                <i class="fa-brands fa-node"></i>
                <p>NODEJS</p>
            </div>
            <div>
                <i class="fa-solid fa-database"></i>
                <p>MYSQL</p>
            </div>
            <div>
                <i class="fa-brands fa-github"></i>
                <p>GITHUB</p>
            </div>
            <div>
                <i class="fa-brands fa-git-alt"></i>
                <p>GIT</p>
            </div>

        </div>
    </div>
</template>

<script>
    export default{
        name: "SkillsVue"
    }
</script>

<style scoped>
.skills{
    display: grid;
    grid-template-columns: repeat(3,1fr);
}
h1{
    color: #85CDFD;
    margin-top: 5rem;
    margin-bottom: 2rem;
}
i{
    font-size: 10rem;   
}

@media screen and (max-width: 900px){
    .skills{
    display: grid;
    grid-template-columns: repeat(2,1fr);
}
}

@media screen and (max-width: 600px){
    .skills{
    display: grid;
    grid-template-columns: 1fr;
}
}
</style>