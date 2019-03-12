<template>
  <div id="app">
    <Header />
    <router-view/>
  </div>
</template>
<script type="text/javascript">
import Header from './components/layouts/header'

export default {
  name: 'app',
  components: {
    Header
  }
}
</script>

<style>
  *{
    box-sizing: border-box;
    margin: 0;
    padding: 0;

  }

  body {
    font-family: Arial, Helvetica, sans-serif;
    line-height: 1.4;
  }
  .btn{
    display: inline-block;
    border: none;
    background-color: #555;
    color: #fff;
    padding: 7px 20px;
    cursor: pointer;

  }
  .btn:hover{
    background-color: #666;
  }
</style>
