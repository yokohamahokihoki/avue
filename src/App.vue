<template>
  <div id="app">
    <header>
      <h1>Actlogy</h1>
    </header>
    <router-view/>
  </div>
</template>

<script>
export default {
  name: 'App'
}
</script>

<style>
*{margin:0;padding:0}
body{font-family:sans-serif;background:#222;color:#FFF;line-height:1.5}
header{color:#FFF;background:rgba(0,0,0,0.8);width:100%;position:fixed;top:0}
h1{font-size:2rem;font-family:'Ubuntu';text-align:center}
main{margin-top:3rem}
</style>
