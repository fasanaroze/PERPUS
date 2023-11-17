<template>
  <div>
      <div class="nav-container">
          <img src="@/assets/img/smk.png" class="logosmk"/>
          <div class="headerText">
              <h1>PERPUS DIGITAL</h1>
          </div>
          <h4>SMKN 4 TASIKMALAYA</h4>
          <img src="@/assets/img/f.png" class="logoclub"/>
          
          
      </div>
  </div>
</template>

<script setup>

</script>
<style scoped>
*{
margin: 0;
z-index: 1;
}
.nav-container {
  background-color:#1e1e1e;
  width: 100%;
  height: 150px;
  display: flex;
  justify-content: space-evenly;
  align-items: center;
  position: fixed;
  top: 0;
  left: 0;
  right: 0;
}

.logoclub {
  width: 100px;
  height: 90px;
}

.logosmk{
  width: 111px;
  height: 126px;

}
h1 {
  color: #ffffff;
  text-align: right;
  font-family: '';
  font-size: 20px;
  letter-spacing: 9px;
  font-weight: 50;
  line-height: normal;

}

h4{
  color: #ffffff;
  text-align: right;
  font-family: '';
  font-size: 20px;
  letter-spacing: 9px;
  font-weight: 50;
  line-height: normal;
}

@media (max-width: 520px) {
  .nav-container {
      background-color:#1e1e1e;
      width: 100%;
      height: 80px;
      display: flex;
      justify-content: space-evenly;
      align-items: center;
      position: fixed;
      top: 0;
      left: 0;
      right: 0;
  }
  
  .logosmk {
      width: 150px;
      height:100px;
  }
  
  }
  .logosmk{
      width: 46.077px;
      height: 50px;
  
  }
  h1 {
      color: #ffffff;
      text-align: right;
      font-family: '';
      font-size: 26px;
      letter-spacing: 4px;
      font-style: 'light';
  
  }
  
  h4{
    color: #ffffff;
      text-align: right;
      font-family: '';
      font-size: 26px;
      letter-spacing: 4px;
      font-style: 'light';
  
  }

@media (max-width: 820px) {
  .nav-container {
      background-color:#1e1e1e;
      width: 100%;
      height: 130px;
      display: flex;
      justify-content: space-evenly;
      align-items: center;
      position: fixed;
      top: 0;
      left: 0;
      right: 0;
  }
  
  .logoclub {
      width: 100px;
      height:118px;
  }
  
  
  .logosmk{
      width: 80.077px;
      height: 80px;
  
  }
  h1 {
      color: #1e1e1e;
      text-align: center;
      font-family: '';
      font-size: 15px;
      letter-spacing: 2px;
      font-style: 'light';
  
  }
  
  h4{
    color: #1e1e1e;
      text-align: center;
      font-family: '';
      font-size: 15px;
      letter-spacing: 2px;
      font-style: 'light';
  
  }
}
</style>