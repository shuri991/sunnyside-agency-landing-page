<template>
    <div class="text-main1">
         <h2>Transform your brand</h2>

        <p class="paragraph1">We are a full-service creative agency specializing 
         in helping brands grow fast. Engage your clients 
         through compelling visuals that do most of the 
         marketing for you.</p>

         <p>Learn more</p>
    </div>

    <div class="text-main2">
        <h2>Stand out to the right audience</h2>

        <p class="paragraph1">Using a collaborative formula of designers, researchers, 
        photographers, videographers, and copywriters, we’ll build and 
        extend your brand in digital places.</p>

        <p>Learn more</p>
    </div>

    <div class="text-main3">
        <h2>Graphic design</h2> 
        <p class="paragraph2">
          Great design makes you memorable. 
          We deliver artwork that underscores your brand message and 
          captures potential clients’ attention.
        </p>
    </div>

    <div class="text-main4">
         <h2>Photography</h2> 
        <p class="paragraph2">
         Increase your credibility by getting the
         most stunning, high-quality photos that improve your business image.
        </p>
    </div>
</template>

<script>
export default {
    name: 'main',
    props: {
        msg: String
    }
}
</script>

<style scoped>
.text-main1,
.text-main2 {
   display: flex;
   flex-direction: column;
   justify-content: center;
   padding: 60px;
   
}

.text-main1 h2,
.text-main2 h2{
    margin-bottom: 30px;
    font-size: 2rem;
}

.paragraph1{
    margin-bottom: 30px;
}

.text-main3,
.text-main4{
    display: flex;
    flex-direction: column;
    justify-content: flex-end;
    align-items: center;
}

.text-main3{
    grid-column: 1 / 2;
    grid-row: 3 /4;
    position: relative;
} 

.text-main4{
    grid-column: 2 / 3;
    grid-row: 3 / 4;
    position: relative;
}

.text-main3 h2,
.text-main4 h2{
 font-size: 1.5rem;
 margin-bottom: 50px;
}

.paragraph2{
    margin-bottom: 50px;
    padding: 0px 50px;
}

</style>