<template>
    <img src="../assets/logo.svg" alt="">
    <div class="header">
        
        <ul>
            <li>About</li>
            <li>Services</li>
            <li>Projects</li>
        </ul>
        <button class="contact">Contact</button>
    </div>

    <div class="main-title">
       <h1>we are creatives</h1>
    </div>
</template>

<script>
export default {
    name: 'header',
    props: {
        msg: String
    }
}
</script>

<style scoped>

.header{
    display: flex;
    justify-content: end;
    position: relative;
    padding: 40px;
}

img{
    position: absolute;
    margin: 30px;
    width: 15%;
}

ul{
    display: flex;
    justify-content: end;
    list-style: none;
}

li{
     color: white;
     margin-right: 50px;
}

.contact{
    background: white;
    color: black;
    
}

.main-title{
    position: relative;
    display: flex;
    align-items: center;
    flex-direction: column;
    margin-top: 50px;
}
.main-title h1{
    color: white;
    font-family:'Fraunces', serif;
    font-weight: 900;
    font-size: 5rem ;
}



</style>