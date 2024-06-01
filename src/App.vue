<template>
  <img alt="Mamur Logo" src="./assets/mamurlogo.png">
  <BemVindo msg="Bem Vindo!"/>
  <NossasLojas/>
  <CadastroCliente/>
  <EscolhaProduto/>
</template>

<script>
import BemVindo from './components/Bemvindo'
import NossasLojas from './components/NossasLojas'
import CadastroCliente from './components/CadastroCliente'
import EscolhaProduto from './components/EscolhaProduto'

export default {
  name: 'App',
  components: {
    BemVindo, NossasLojas, CadastroCliente, EscolhaProduto
  }
}
</script>

<style>
#app {
  font-family: Avenir, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
  margin-top: 60px;
}
</style>
