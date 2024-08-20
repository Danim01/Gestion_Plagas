<template>
  <h1>Bienvenido!</h1>
  <main>
    <BotonDiagnostico class="diagnostico"></BotonDiagnostico>
    <BotonAlertas class="alertas"></BotonAlertas>
    <BotonConfigurar></BotonConfigurar>
    <BarraInferior></BarraInferior>
  </main>
</template>

<script setup>
import BotonDiagnostico from "./components/BotonDiagnostico.vue"
import BotonAlertas from "./components/BotonAlertas.vue"
import BotonConfigurar from "./components/BotonConfigurar.vue"
import BarraInferior from "./components/BarraInferior.vue"
</script>

<style>
  main {
    display: flex;
    flex-direction: column;
    margin: auto;
  }
</style>
