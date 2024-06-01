<template>
  <div class="hello">
    <label>Selecione a unidade mais próxima de você <br></label>
    <select name="unidade" id="unidade">
      <option value="">Selecione</option>
      <option value="PT">Unidade 1 Jardim Petrópolis</option>
      <option value="SM">Unidade 2 Santa Marta</option>
      <option value="VG">Unidade 3 Várzea Grande</option>
    </select>

  </div>
</template>

<script>
export default {
  name: 'NossasLojas',
}
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped>
h3 {
  margin: 40px 0 0;
}
ul {
  list-style-type: none;
  padding: 0;
}
li {
  display: inline-block;
  margin: 0 10px;
}
a {
  color: #42b983;
}
label{
  font-size: 16px;
  font-weight:bolder ;
}
select{
  color: red;
  margin: 10px;
}
</style>
