<template>
    <section class="contato" id="contato">
        <div class="container">
            <h2>Contato: </h2>
            <form>
                <Input type="text" nome="nome" label="Nome:" placeholder="Insira seu nome..." is_input />
                <Input type="email" nome="email" label="E-mail:" placeholder="Insira seu e-mail..." is_input />
                <Input nome="texto" placeholder="Insira sua mensagem" /> 
                <button type="submit" name="acao">Enviar</button>
            </form>
        </div>
    </section>
</template>

<script>
import Input from "./Input.vue";
export default{
    name: "Contato",
    components:{
        Input
    }
}
</script>

<style scoped>
form{
max-width: 700px;
margin: auto;
}
.contato{
margin-top: 20px;
margin-bottom: 20px;
}
h2{
font-size: 32px;
border-bottom: 1px solid #333;
margin-bottom: 10px;
}

p{
font-size: 18px;
}

button{
    text-align: center;
    background-color: steelblue;
    color: white;
    padding: 10px 20px;
    border: 0;
    cursor: pointer;
}
</style>
