

<template>
    <div id="app">
        
        <Navigation />
        <Background />
        <Images />
    </div>
    

</template>
    
<script>
    
    import Navigation from "./components/Navigation.vue";
    import Background from "./components/Background.vue";
    import Images from "./components/Images.vue";
    export default {
      
      components: {
        Navigation,
        Background,
        Images
      }
    }
</script>
    
<style lang="css">

</style>