<template>
  <div class="home">
    <PageTitle
      icon="fa fa-home"
      main=" Dashboard"
      sub="Prefeitura de Silveirânia"
      but="false"
      search="false"
    
    />
  </div>
</template>

<script>
import PageTitle from "@/components/template/PageTitle.vue";
export default {
  name: "HomeDashboard",
  components: { PageTitle },
};
</script>

<style>

</style>