cd<template>
        
    
    <div id="align">
        <h2>Grupos e Usuários</h2>
        
        <button onclick="myFunction(#)" class="btn1"><span>SALVAR</span></button>
        <button onclick="myFunction(#)" class="btn2"><span>VOLTAR</span></button>
        
          
    </div>

        
</template>

<!-----------------------------SCRIPT------------------------------------------------------------------->

<script>
export default {
    
}
</script>

<!------------------------------STYLE .SCSS-------------------------------------------------------------->

<style scoped>

#align {
  font-style: normal;
  font-family: Arial, Helvetica, sans-serif;
  padding: 5px 5px 5px 120px;
  color: #ffffff;
  background-color: #56728f;
  display: flex;
}

.btn1 {
  text-align: center;
  color: #ffffff;
  transition: all 0.5s;
  cursor: pointer;
  margin-left: 550px;
  padding: 7px;
  width: 115px;
  border-radius: 20px;
  border: none;
  /*background: linear-gradient(0deg, #3b8c48 0%, #b9ff09 100%)*/
  background: linear-gradient(0deg, #bdbbc0 0%, #dfe7f2 100%)
}

.btn2 {
    
  text-align: center;
  color: #ffffff;
  transition: all 0.5s;
  cursor: pointer;
  margin-left: 175px;
  padding: 7px;
  width: 115px;
  border-radius: 20px;
  border: none;
  /*background: linear-gradient(0deg, #3b8c48 0%, #b9ff09 100%)*/
  background: linear-gradient(0deg, #bdbbc0 0%, #dfe7f2 100%)
}

/*------------------------------animação  btn1--------------------------------------------------------------*/

.btn1:hover { 
  
  background: rgb(169, 250, 39);
    
}

.btn1:focus { 
  
  background: linear-gradient(0deg, #3b8c48 0%, #b9ff09 100%);
    
}

.btn1:active {
  
  position: relative;
  top: 2px;
    
}

.btn1 span {
  cursor: pointer;
  display: inline-block;
  position: relative;
  transition: 0.5s;
}

.btn1 span:after {
  content: '\25C4';
  position: absolute;
  opacity: 0;
  top: 0;
  right: -20px;
  transition: 0.5s;
}

.btn1:hover span {
  padding-right: 25px;
}

.btn1:hover span:after {
  opacity: 1;
  right: 0;
}

/*------------------------------animação  btn2--------------------------------------------------------------*/

.btn2:hover {
  
  background: rgb(169, 250, 39);
    
}

.btn2:focus { 
  
  background: linear-gradient(0deg, #3b8c48 0%, #b9ff09 100%);
    
}

.btn2:active {
  
  position: relative;
  top: 2px;
    
}

.btn2 span {
  cursor: pointer;
  display: inline-block;
  position: relative;
  transition: 0.5s;
}

.btn2 span:after {
  content: '\25ba';
  position: absolute;
  opacity: 0;
  top: 0;
  left: -35px;
  transition: 0.5s;
}

.btn2:hover span {
  padding-left: 25px;
}

.btn2:hover span:after {
  opacity: 1;
  left: 0;
}

</style>