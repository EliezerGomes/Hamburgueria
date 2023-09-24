<template>
  <Banner/>
  <div class="main-container">
   <h1>Monte o seu burguer:</h1>
   <Form />
  </div>
</template>

<script>
  import Banner from "../components/Banner.vue"
  import Form from "../components/Form.vue"

  export default {
    components: {
      Banner,
      Form
    }
  }
</script>
