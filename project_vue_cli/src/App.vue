<template> 
  
<headerSight/>
<mainFirstPage/>
<footerSight/>
<hr>
<headerSight/>
<mainTwoPage/>
<footerSight/>
<hr>
<headerSight/>
<mainThirdPage/>
<footerSight/>
</template>

<script>
import headerSight from './components/headerSight.vue';
import mainTwoPage from './components/mainTwoPage.vue';
import mainFirstPage from './components/mainFirstPage.vue';
import mainThirdPage from './components/mainThirdPage.vue';
import footerSight from './components/footerSight.vue';
export default {  
  components: {
    headerSight,
    footerSight,
    mainTwoPage,
    mainFirstPage,
    mainThirdPage,
  }
}
</script>

<style lang="scss">

</style>
