<template>
    <div class="container">
       <img class="image-container" src="../assets/logo.svg" alt=""> 
       <div class="container-list">
          <ul>
             <li>About</li>
             <li>Services</li>
             <li>Projects</li>
             <li>Contact</li>
          </ul>
        </div>
        <div class="container-icons">
          <div class="icons">
            <img src="../assets/icon-facebook.svg" alt="">
            <img src="../assets/icon-instagram.svg" alt="">
            <img src="../assets/icon-twitter.svg" alt="">
            <img src="../assets/icon-pinterest.svg" alt="">
          </div>
       </div>
       <p> Challenge by Frontend Mentor. Coded by Your Name Here. </p>
    </div>
</template>

<script>
export default {
    
}
</script>

<style scoped>
.container{
    background: hsl(168, 56%, 65%);
    height: 300px;
    width: 100vw;
    justify-content: center;
    display: flex;
    flex-direction: column;
    align-items: center;
}

.image-container{
    width: 10%;
    margin: 40px;
}

.container-list ul{
    list-style: none;
    display: flex;
    color: hsl(167, 40%, 24%);
}

.container-list li{
    margin-right: 30px;
}

.container-icons{
    margin-top: 80px;
}

.container-icons img{
    margin-right: 30px;
    margin-bottom: 30px;
}
</style>