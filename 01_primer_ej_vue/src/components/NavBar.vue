<template>
   <div id="navegador">
<ul>
<li><a href="#">Home</a></li>
<li><a href="#">About</a></li>
<li><a href="#">Contact</a></li>
<li><a href="#">Shop</a></li>
</ul>
</div>
</template>

<script setup>

</script>

<style>
#navegador ul{
   list-style: none;
   text-align: center;
   display:flex;
   justify-content:space-around;
   text-decoration:none;
}

a{
    color: #42b983;
    text-decoration:none;
    font-size: 3rem;
}
a:hover{
    background-color: #B84277;
    color:White;
    padding: 2rem;
    border-radius:5%;
 }



</style>