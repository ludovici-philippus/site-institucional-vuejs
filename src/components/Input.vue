<template>
    <div class="form-group">
        <label v-if="is_input" :for="nome">{{ label }}</label>
        <input v-if="is_input" :type="type" :id="nome" :name="nome" :placeholder="placeholder"/>
        <textarea v-else :id="nome" :name="nome" :placeholder="placeholder"></textarea>
    </div>
</template>

<script>
export default {
    name:"Input",
    props:{
        type: String,
        nome: String,
        label: String,
        placeholder: String,
        is_input: Boolean,
    }
}
</script>

<style scoped>
.form-group{
max-width: 700px;
margin: 10px auto;
}
label{
font-size: 20px;
}
input{
    width: 100%;
    height: 44px;
    padding-left: 4px;
}
textarea{
    width: 100%;
    height: 144px;
    padding: 10px;
    resize: vertical;
}
</style>
