<template>
    <header>
        <div class="overlay"></div>
        <div class="header__content">
            <div class="content__logo">
                <router-link to="/"><h1>Empresa</h1></router-link> 
            </div>
            <a class="btn" href="#contato">Entre em Contato!</a>
        </div>
    </header>
</template>

<script>
export default{
name: "Header"
} 
</script>

<style scoped>
header{
    width: 100%;
    min-height: 50vh;
    background-image: url("../assets/images/bg.jpg");
    background-attachment: fixed;
    background-size: cover;
    background-position: center;
    position: relative;
    z-index: 1;
    margin-bottom: 10px;
    }
.overlay{
    position: absolute;
    top: 0;
    left: 0;
    z-index: 2;
    background-color: rgba(0, 0, 0, 0.5);
    width: 100%;
    min-height: 50vh;
}

.header__content{
    position: absolute;
    top: 50%;
    z-index: 3;
    width: 100%;
    text-align: center;
}

.header__content a{
    text-decoration: none;
    color: white;
}

.header__content h1{
    margin-bottom: 10px;
}

.btn{
    display: inline-block;
    background-color: orange;
    padding: 8px 16px;
    font-weight: bold;
    font-size: 16px;
    transition: 0.5s;
}

.btn:hover{
    background-color: #ff8300;
}

</style>
