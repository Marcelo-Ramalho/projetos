<template>
              
  <div>

    <div class="container_t">

        <h3>Dados do Grupo do Usuário</h3>

    </div>

   <div class="container1"> <!--"container_li flexivel horizontal vertical quebra"-->
     
     <form action="#">
       
        <div class="item1"><label for="#" class="lcodigo">Código</label></div>
        <div class="item1"><input type="text" id="Código" class="icodigo" name="Código" placeholder="Código"></div>
                      
     </form>

    
    <div class="container2"> <!--"container_li flexivel horizontal vertical quebra"-->
     
     <form action="#">
       
        <div class="item2"><label for="#" class="lnome">Nome</label></div>
        <div class="item2"><input type="text" id="Nome" class="inome" name="Nome" placeholder="Nome"></div>
               
     </form>
     
    </div>    
     
    </div>    

  </div>
   
</template>


<!-----------------------------SCRIPT------------------------------------------------------------------->

<script>
export default {
  
}
</script>

<!------------------------------STYLE .SCSS-------------------------------------------------------------->

<style scoped>




.item1 {
  margin: 5px;
  font-family: 'Segoe UI', Tahoma, Geneva, Verdana, sans-serif;
  background: #e8e4ec;
  font-size: 1em;
  
  
}

.item2 {
  margin: 5px;
  font-family: 'Segoe UI', Tahoma, Geneva, Verdana, sans-serif;
  background: #e8e4ec;
  font-size: 1em;
  
  
}

.container_t {
  padding-left: 350px;
  padding-top: 20px;
  padding-bottom: 7px;  
  text-align: left;
  background-color: #e8e4ec;
}

.container1 {
  max-width: 100px;
  padding-left: 346px;
  display: flex;
  background-color: #e8e4ec;
  
}

.icodigo{
  max-width: 60PX;
}

.container2 {
  max-width: 500px;
  padding-left: 100px;
  padding-right: 413px;
  padding-bottom: 35px;
  display: flex;
  background-color: #e8e4ec;
}

input[type=text]{
  width: 640px;
  height: 30px;
  padding-left: 10px;
  background-repeat: no-repeat;
  background-position: 10px 10px; 
  transition: initial 0.4s ease-in-out;;
  border-radius: 4px;
  border: none;
  background: #c2ff8d;
}

.inome[type=text]:focus,
.inome[type=text]:valid {
  outline-style: none;
  background-color: #7cd12c;
  color: #fff;
}

.icodigo[type=text]:focus,
.icodigo[type=text]:valid {
  outline-style: none;
   background-color: #7cd12c;
  color: #fff;
}

/*input.inome:hover, input.inome:focus{
  background: #e8e4ec;
  }

input.icodigo:hover, input.icodigo:focus{
  background: #e8e4ec;
  }*/

</style>






















