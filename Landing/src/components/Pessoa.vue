<template>
<H2>Esta é a descrição da Pessoa: {{ nome }}</H2>
<p>Essa se Pessoa Descreve dessa Forma : {{ Descricao }} </p>
<p v-show="MostrarEmail"> Aooooba</p>

<button @click="ShowEmail" >
 {{ TextButton }}
</button>



<ol>
<li v-for="v in Lingaguem">
    {{v}}
</li>
</ol>
<p>Para acessare meu portifolio <a v-bind:href="Links" target="_blank">Basta Clicar aquuiu</a></p>
</template>
<script>
export default{
name:"Pessoa",
 data(){
    return{

    nome:"Elder",
    Descricao:"Essa pessoa é petistas entao faz o L ",
    Lingaguem:["JavaScript" , "Java" , "HTML"],
    Links:'https://github.com/Elder-levi/Langing_page',
    MostrarEmail:false,
    TextButton: 'Mostra E-mail'


    }
  },
  methods:
  {
   ShowEmail(){
    
    this.MostrarEmail = !this.MostrarEmail;
    if(!this.MostrarEmail)
    {
        this.TextButton = 'Mostra E-mail' 
    }
    else
    { 
        this.TextButton = 'Esconder E-mail'

    }



   }






  }
}
</script>
<style scoped>
</style>