<template>
  <footer class="container-fluid text-center">
    <div class="row">
        <p class="lead">Joshua's Portfolio &copy; <span>{{ cYear }}</span></p>
    </div>
  </footer>
</template>

<script>
export default {
    name: "FooterComp",
    data(){
        return{
            cYear: new Date().getUTCFullYear()
        }
    }
}
</script>

<style>

</style>