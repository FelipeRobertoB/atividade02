<template>
    
    <h2>Selecione seu Combo</h2>

    <form>
        <label for="combos">Combos:</label>
        <select id="combos" name="combos" required>
            <option value="" disabled selected>Selecione uma opção</option>
            <option value="combo1">Combo 1</option>
            <option value="combo2">Combo 2</option>
            <option value="combo3">Combo 3</option>
        </select>

        <button type="submit">Enviar</button>
    </form>
</template>

<script>
    export default{
        name: 'EscolhaProduto'
    }
</script>