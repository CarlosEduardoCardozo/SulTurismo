<template>
<div class="content">
  <div class="jpg">
    <img class="logosul" src="logoSulTurismo.jpeg">
  </div>
  <div class="infoHeader">
    <span>Quem somos?</span>
    <span>Contato</span>
    <span>Nossos Serviços</span>
  </div>
</div>
</template>
<style scoped>
.content{
  display: flex;
  flex-direction: row;
  align-items: center;
  background-color: rgb(0, 0, 0);
  height: 100px;
  border-radius: 15px;
  justify-content: space-between;
  padding: 0 10%;
}
.logosul{
  width: 75px;
}
.infoHeader{
  color: #ffff;
  padding: 10%;
  font-family: Arial, Helvetica, sans-serif;
}
.infoHeader :hover{

  background-color: #fa943a;
  height: 100px;
}

</style>