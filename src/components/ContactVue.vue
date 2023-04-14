<template>
    <h1 id="contact">CONTACT ME</h1>
    <div class="container">
        <div class="contact">
            <h3>GET IN TOUCH</h3>
            <p><i class="fa-solid fa-envelope"></i> giftnkz6@gmail.com</p>
            <p><i class="fa-solid fa-phone"></i> 0790299233</p>
            <p><i class="fa-solid fa-address-book"></i> Kenwyn, Cape Town</p>
            <p><i class="fa-brands fa-linkedin"></i> <a href="https://www.linkedin.com/in/gift-mahlangu-223262180/"> giftmahlangu</a></p>
        </div>

        <form action="https://formspree.io/f/mrgdkjgy" method="POST">
            <div class="mb-3">
                <label for="exampleFormControlInput1" class="form-label">Name</label>
                <input type="email" class="form-control" id="exampleFormControlInput1" required placeholder="Name">
            </div>
            <div class="mb-3">
                <label for="exampleFormControlInput1" class="form-label">Email address</label>
                <input type="email" class="form-control" id="exampleFormControlInput1" required placeholder="name@example.com">
            </div>
            <div>
                <label for="exampleFormControlTextarea1" class="form-label">Write Me a Message</label>
                <textarea class="form-control" id="exampleFormControlTextarea1" rows="3" required placeholder="Leave a Message"></textarea>
            </div>
            <div>
                <button type="submit" class="btn">Submit</button>
            </div>

        </form>
    </div>
</template>

<script>
export default {
    name: "ContactVue"
}
</script>

<style scoped>
    a{
        text-decoration: none;
        color: #DEFCF9;
    }
    .contact{
        text-align: start;
        margin-top: 1rem;
        margin-left: 4rem;
    }

    h3{
        margin-bottom: 2rem;
        color: #85CDFD;
        font-size: 1.9rem;
    }

    button{
        background-color: #85CDFD;
        color: #DEFCF9;
        margin-top: 1rem;
        margin-bottom: 2rem;
        width: 12rem;
        height: 4rem;
        font-size: large;
    }

    button:hover{
        background-color: #85CDFD;

    }

    

    .container .contact i{
        font-size: 2rem;
    }

    .container{
        display: grid;
        grid-template-columns: repeat(2, 1fr);
    }
    p{
        margin-bottom: 2rem;
        font-size: 1.2rem;
    }

    h1{
        color: #85CDFD;
        margin-top: 6rem;
        margin-bottom: 3rem;
    }

    textarea{
        height: 8rem;
    }

    @media screen and (max-width: 770px){
        .container{
        display: grid;
        grid-template-columns: 1fr;
    }

    .contact{
        text-align: start;
        margin-top: 1rem;
        margin-left: 4rem;
        margin: auto;
    }

    h3{
        font-size: 1.6rem;
    }

    }
</style>

