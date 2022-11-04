<template>
    <nav>
        <ul id="menu">
            <li>
                <router-link to="/">Inicio-Home</router-link>
            </li>
             <li>
                <router-link to="/mutiplicar">Mutiplicar</router-link>
            </li>
        </ul>
    </nav>
</template>

<script>
export default{
    name:"MenuComponents"
   
};

</script>

 <style scoped>
 ul#menu li {
   display: inline;
   margin-left: 2%;
  
 }
 </style>

