<template>
  <BannerComponent/>
  <div class="main-container">
    <h1>Monte o seu burguer: </h1> <br>
    <FormComponent />
  </div>
</template>

<script>
  import BannerComponent from '@/components/BannerComponent.vue'
  import FormComponent from '@/components/FormComponent.vue'

  export default {
    name: 'HomeView',
    components: {
      BannerComponent,
      FormComponent
    }
  }
</script>
