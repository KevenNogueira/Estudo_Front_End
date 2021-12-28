<template>
    <div class="alinhar"> 
        <h2>Grupo de usuários</h2>
            <button @click="salvar()" class="salvar">Salvar</button>
                <button @click="myFunction()" class="voltar">Voltar</button>
    </div>
</template>

<script>

</script>




<style scoped>
.alinhar{
    color: black;
    font-style: normal;
    font-family: 'Times New Roman', Times, serif;
    padding: 5px 5px 5px 120px;
    display: flex; 
     
}
.salvar{
    color: black;
    text-align: center;
    cursor: pointer;
    padding: 7px;
    width: 120px;
    border-radius: 20px 150px;
    border: none;
    background: green;
   }
.voltar{
    color: black;
    text-align: center;
    cursor: pointer;
    padding: 7px;
    width: 120px;
    border-radius: 150px 20px;
    border: none;
    background:grey;
}
</style>