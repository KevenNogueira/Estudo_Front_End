<template>
    <div>
        <div class="titulo"> 
            <h3>Dados do Grupo de Usuário</h3>
        </div>
            <div class="codigo">
                <Form action="*"> 
                    <div class="iten1">
                        <Label class="numero">Código
                        </Label>
                    </div>
                        <div class="inten1">
                            <Input type="text" class="1" placeholder="Código"></Input>
                         </div>
                </Form>
            </div>
                <div class="nome"> 
                    <Form action="*">
                        <div class="inten2">
                            <Label class="texto">Nome
                            </Label>
                        </div>
                            <div class="iten2">
                               <Input type="text" class="2" placeholder="Nome"></Input> 
                            </div>
                                

                    </Form>
                </div>       
    </div>
</template>
<script>


</script>
<style scoped>
.titulo{
    color: black;
    font-style: normal;
    font-family: 'Times New Roman', Times, serif;
    
}
.codigo{
    padding: 7px;
    width: 120px;
    border-radius: 20px 150px;
    
}
.nome{
    
    padding: 7px;
    width: 120px;
    border-radius: 20px 150px;
}



</style>