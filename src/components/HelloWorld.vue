<template>
  <div class="hello" style="margin-top: 120px;">
    <h1>{{ msg }}</h1>
    <!-- <h3>- get it done -</h3> -->
    <br>
    <date-picker v-model="date" :config="options"></date-picker>
    <!-- <label class="mt-3" for="datepicker-dateformat2">Choose Date: </label>
    <b-form-datepicker
      id="datepicker-dateformat2"
      :date-format-options="{ year: 'numeric', month: 'numeric', day: 'numeric' }"
      locale="en"
    ></b-form-datepicker>
    <div>
        <b-form-datepicker v-model="value" :min="min" :max="max" locale="en"></b-form-datepicker>
      </div> -->
    <div class="row" id="input">
        <form class="col-6">
          <input type="text" placeholder="Create a new to-do..." class="form-control">
        </form>
      </div>
    <div class="container" id="arra">
      
      <div class="row mb-6" style="margin-top: 25px;">
      <br>
        <div  class="col-12">
          <ul  class="list-group">
            <li  class="d-flex align-items-center list-group-item">
              <button class="btn border-0 flex-grow-1 text-left shadow-none">
                <span>Do the dishes</span>
              </button>
              <button class="btn btn-outline-primary border-0 ml-2">
                <font-awesome-icon icon="edit" />
              </button>
              <button  class="btn btn-outline-danger border-0">
                <font-awesome-icon icon="trash-alt" />
              </button>
            </li>
            <li  class="d-flex align-items-center list-group-item">
              <button  class="btn border-0 flex-grow-1 text-left shadow-none">
                <span>Take out the trash</span>
              </button>
              <button class="btn btn-outline-primary border-0 ml-2">
                <font-awesome-icon icon="edit" />
              </button>
              <button class="btn btn-outline-danger border-0">
                <font-awesome-icon icon="trash-alt" />
              </button>
            </li>
            <li class="d-flex align-items-center list-group-item">
              <button  class="btn border-0 flex-grow-1 text-left shadow-none">
                <span>Finish doing laundry</span>
              </button>
              <button class="btn btn-outline-primary border-0 ml-2">
                <font-awesome-icon icon="edit" />
              </button>
              <button class="btn btn-outline-danger border-0">
                <font-awesome-icon icon="trash-alt" />
              </button>
            </li>
            <li class="d-flex align-items-center list-group-item">
              <button class="btn border-0 flex-grow-1 text-left shadow-none">
                <span>hello</span>
              </button>
              <button class="btn btn-outline-primary border-0 ml-2">
                <font-awesome-icon icon="edit" />
              </button>
              <button class="btn btn-outline-danger border-0">
                <font-awesome-icon icon="trash-alt" />
              </button>
            </li>
            </ul>
          </div>
        </div>
      </div>
  </div>
</template>

<script>
export default {
  name: 'HelloWorld',
  props: {
    msg: String
  }
    
}
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped>
/* @import url('https://fonts.googleapis.com/css2?family=Luckiest+Guy&display=swap');
#app {
  font-family: 'Luckiest Guy', cursive;
  display: flex;
  align-items: center;
  justify-content: center; */
    
    
/* } */
#input{
  display: flex;
  align-items: center;
  justify-content: center;
}
#arra{
  display: flex;
  align-items: center;
  justify-content: center;
}
ul {
  list-style-type: none;
  padding: 0;
}
li {
  display: inline-block;
  margin: 0 10px;
}
a {
  color: #42b983;
}
</style>
