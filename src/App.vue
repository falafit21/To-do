<template>
  <div id="app">
    <!-- <img alt="Vue logo" src="./assets/logo.png"> -->
    <HelloWorld msg="MY TO-DOs"/>
    <!-- <detail name="example-datepicker" label="Choose Date"> -->

    
  </div>
</template>

<script>
import HelloWorld from './components/HelloWorld.vue'
// import 'bootstrap/dist/css/bootstrap.css';
  
//   // Import this component
//   import datePicker from 'vue-bootstrap-datetimepicker';
  
//   // Import date picker css
//   import 'pc-bootstrap4-datetimepicker/build/css/bootstrap-datetimepicker.css';
// import { BFormDatepicker } from 'bootstrap-vue'
// Vue.component('b-form-datepicker', BFormDatepicker)
// import Detail from './components/Detail.vue'

export default {
  name: 'App',
  components: {
    HelloWorld
  }
  
}

    
  
</script>

<style>

@import url('https://fonts.googleapis.com/css2?family=Luckiest+Guy&display=swap');
#app {
  font-family: 'Luckiest Guy', cursive;
  
    
}
h1 {
  display: flex;
  align-items: center;
  justify-content: center;
  font-size: 75px;
  /* color: white; */

}
h3{
  display: flex;
  align-items: center;
  justify-content: center;
  /* background-color: 	#ffbf00; */
  
}

html, 
body {
    margin: 0;
    padding: 0;
    background-color:#ffa812;
}

</style>
