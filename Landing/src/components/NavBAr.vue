<template>
<nav>
<ul class="direito">
    <H1 class="Title">Nome da Loja</H1>
    <li><a href="#">Moda Masculina</a></li>
    <li><a href="#">Moda Feminina</a></li>
    <li><a href="#">Objetos</a></li>
    <li><a href="#">Sobre</a></li>
</ul>

<svg xmlns="http://www.w3.org/2000/svg" viewBox="0 0 1440 320">

    
  <path fill="white" fill-opacity="1" d="M0,256L26.7,240C53.3,224,107,192,160,176C213.3,160,267,160,320,186.7C373.3,213,427,267,480,288C533.3,309,587,299,640,261.3C693.3,224,747,160,800,122.7C853.3,85,907,75,960,80C1013.3,85,1067,107,1120,144C1173.3,181,1227,235,1280,266.7C1333.3,299,1387,309,1413,314.7L1440,320L1440,0L1413.3,0C1386.7,0,1333,0,1280,0C1226.7,0,1173,0,1120,0C1066.7,0,1013,0,960,0C906.7,0,853,0,800,0C746.7,0,693,0,640,0C586.7,0,533,0,480,0C426.7,0,373,0,320,0C266.7,0,213,0,160,0C106.7,0,53,0,27,0L0,0Z"></path>
</svg>

</nav>
</template>
<script>
export default{
    name:'Cabecalho',
}
</script>
<style scoped>


 body{
  margin:0;
  padding:0;
  display: flex;
  place-items: center;
  align-items: flex-start;
 }
nav{
    display: flex;
    flex-direction: row;
    justify-content: space-evenly;
}
 ul{
    display: flex;
    flex-direction: row;
    align-items: center;
 }
 li , .Title {
     padding-right:7em ; 
      list-style: none;

 }
a{
    text-decoration: none;
}
</style>
