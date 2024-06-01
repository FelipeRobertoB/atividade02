<template>
    <div class="CadastroCliente">
        <h2>Cadastro</h2>
        <form action="CadastroCliente.vue" method="get">
            <label for="nome">Nome Completo:</label>
            <input type="text" id="nome" name="nome" required>

            <label for="endereco">Endereço:</label>
            <input type="text" id="endereco" name="endereco" required>

            <label for="bairro">Bairro:</label>
            <input type="text" id="bairro" name="bairro" required>

            <label for="cidade">Cidade:</label>
            <input type="text" id="cidade" name="cidade" required>

            <label for="complemento">Complemento:</label>
            <input type="text" id="complemento" name="complemento">

            <label for="referencia">Ponto de Referência</label>
            <input type="text" id="referencia" name="referencia">

            <button type="submit">Cadastrar</button>
        </form>
    </div>
</template>

<script>
export default {
  name: 'CadastroClente',
}
</script>

<style scoped>
body {
    font-family: Arial, sans-serif;
    margin: 20px;
    padding: 20px;
    max-width: 600px;
    margin: auto;
}
h2 {
    text-align: center;
}
form {
    display: flex;
    flex-direction: column;
}
label {
    margin-top: 10px;
}
input, select {
    padding: 8px;
    margin-top: 5px;
    border: 1px solid #ccc;
    border-radius: 4px;
}
button {
    margin-top: 20px;
    padding: 10px;
    background-color: #4CAF50;
    color: white;
    border: none;
    border-radius: 4px;
    cursor: pointer;
}
button:hover {
    background-color: #45a049;
}
</style>