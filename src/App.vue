<template>
  <div id="app">
    <Header />
    <router-view/>
  </div>
</template>

<script>
import Header from './components/layout/Header';
export default {
  name: "app",
  components:{
  Header 
  }
}
</script>

<style>
*{
  box-sizing: border_ box;
  margin: 0;
  padding: 0;
}

body {
  font-family: Ariel, Helvetica, sans-serif;
  line-height: 1.4;
}

.btn {
  display: in-line-block;
  border: none;
  background: #555;
  color: #fff;
  padding: 7px 20px;
  cursor: pointer;

}

.btn:hover {
  background: #666;
}
</style>
