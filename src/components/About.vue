<template>
    <div class="about">
        <h1>Hello {{ their_name}} This is a about page</h1>
        <p>Lorem ipsum dolor, sit amet consectetur adipisicing elit. Voluptatibus eligendi doloribus dicta et culpa praesentium saepe, quis eius quibusdam aspernatur dolore labore libero maxime delectus facilis ducimus, illum repellendus quidem.</p>
    </div>
</template>

<script>
export default {
    name: 'Skills', 
    data() {
      return {
        their_name: this.$route.params.name
    
      }
    }   
}
</script>
