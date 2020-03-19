<template>
  <main>
    <h2>互いの技術の向上を</h2>
    <a href=/product/actcms class=card>
      <h3>新しさと柔軟さを</h3><br />
      ACT CMS
    </a>
    <a class=card>
      <h3>自分たちらしさとともに</h3><br />
      SeasideOS
    </a>
  </main>
</template>

<script>
window.onload = function(){
  $('.card').fadeIn();
}
</script>

<style>
main{text-align:center}
h2{text-align:center}
.card{display:none;padding:0.5rem;display:inline-block;width:40%;min-width:350px;text-align:center;color:#FFF;text-decoration:none;vertical-align:top}
h3{display:inline-block}
.card:nth-of-type(2n){
  background: #FFF;
  color: #222
}
</style>
