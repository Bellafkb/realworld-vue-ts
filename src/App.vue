<template>
  <div id="app">
    <navBar/>
    <router-view/>
    <footer/>
  </div>
</template>

<script lang="ts">
import {Vue, Component} from 'vue-property-decorator'
import  footer from '@/components/footer.vue';
import navBar from '@/components/navBar.vue';

@Component({
  components : {
    footer , navBar
  }
})
export default class App extends Vue{

}
</script>


<style>

</style>
