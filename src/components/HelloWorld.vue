<template>
  <div>
   <nav class="navbar navbar-expand-md bg-dark navbar-dark">
  <a class="navbar-brand" href="#">LOGO</a>
  <button class="navbar-toggler" type="button" data-toggle="collapse" data-target="#collapsibleNavbar">
    <span class="navbar-toggler-icon"></span> 
  </button>
 <div class="collapse navbar-collapse" id="collapsibleNavbar">
    <ul class="navbar-nav">
      <li class="nav-item">
        <a class="nav-link" href="#">Menu</a>
      </li>
    </ul>
  </div>
</nav>
<br>
<div class="container">
<div class="form-group">
 <div class="input-group mb-3">
  <input 
      v-model="url"
      type="text" class="form-control" placeholder="Paste url here">
      <div class="input-group-append">
    <button 
    @click="onClick"
    class="btn btn-primary" type="button">OK</button>
  </div>
</div>
</div>
  </div>
  </div>
</template>

<script>
export default {
  name: 'HelloWorld',

  data (){
    return{
      url:null,
    }
  },
  methods:{
     onClick(){
       alert("here")
     }
  }
}
</script>
<style>

</style>
