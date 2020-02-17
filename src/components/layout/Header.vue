<template>
    <div class="header">
      
        <div class="welcome">
          <p>Welcome back, <strong>Divine-Favour</strong></p>
        </div>
        
        <div class="account">
          <div class="content">
            <img src="../../assets/person.png" alt="" id="person">
            <span>Account</span>
            <img src="../../assets/Arrow-down.svg" alt="" id="arrow">
          </div> 
        </div>
                   
    </div>
</template>

<script>
export default {
    name: "Header"
}
</script>

<style scoped>
    .header {
        border-bottom: 1px #dedede solid;
        width: 1366px;
        height: 70px;
        background-color: white;
        display: flex;
        justify-content: space-between;
        margin-left: -30px;
        padding: 0px;
        margin-top: -50px;
    }
    
    .welcome {
        margin-left: 111px;
        margin-top: 10px
    }
    .account {
        width: 131px;
        height: 32px;
        border-radius: 2px;
        border: solid 1px #c6cbd4;
        margin-right: 28px;
        justify-content: center;
        margin-top: 17px
    }
    .content {
        margin-top: 5px;
    }
    span {
        margin: 5px;
    }
    #person {
        width: 11.1px;
        height: 10.6px;
        margin-left: -2px;
        margin-right: 0px;
        margin-top: 5px;
    }
    #arrow {
        width: 8px;
        height: 4.9px;
        margin-left: 30px;
    }
</style>