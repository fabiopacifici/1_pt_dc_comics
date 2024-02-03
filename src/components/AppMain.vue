<script>
import AppJumbotron from './AppJumbotron.vue';
import ComicsList from './ComicsList.vue';
import DcBanner from './DcBanner.vue';

export default {
  name: 'AppMain',
  components: {
    AppJumbotron,
    ComicsList,
    DcBanner
  },
  data() {
    return {

    }
  }


}
</script>
<template>
  <main>

    <AppJumbotron></AppJumbotron>
    <ComicsList></ComicsList>
    <DcBanner></DcBanner>

  </main>
</template>
<style scoped>

</style>