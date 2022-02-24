<template>
    <h1>Client testimonials</h1>
  <div class="cards">
    <div class="card">
        <img src="../assets/image-emily.jpg" alt="Picture">
      <p class="paragraph1">We put our trust in Sunnyside and they delivered,
         making sure our needs were met and deadlines were always hit.
      </p> 
      <p class="paragraph2">Emily R.</p> 
      <p class="paragraph3">Marketing Director</p>
    </div>

    <div class="card">
        <img src="../assets/image-thomas.jpg" alt="Picture">
      <p class="paragraph1">Sunnyside’s enthusiasm coupled with their keen interest in our brand’s 
         success made it a satisfying and enjoyable experience.
      </p> 
      <p class="paragraph2">Thomas S.</p> 
      <p class="paragraph3">Chief Operating Officer</p>
    </div>

    <div class="card">
        <img src="../assets/image-jennie.jpg" alt="Picture">
      <p class="paragraph1">Incredible end result! Our sales increased over 400% when we worked 
         with Sunnyside. Highly recommended!
      </p> 
      <p class="paragraph2">Jennie F.</p> 
      <p class="paragraph3">Business Owner</p>
    </div>
  </div>
</template>

<script>
export default {
    name: 'section-testimonial',
    props: {
        msg: String
    }
}
</script>

<style scoped>

h1{
    display: flex;
    justify-content: center;
    align-items: flex-end;
    height: 200px;
    font-size: 1.5rem;
    text-transform: uppercase;
    margin-bottom: 50px;
    padding-bottom: 30px
}

.cards{
  display: flex;
  justify-content: space-between;
  width: 100%;
}

.card{
  height: 400px;
  padding: 30px;
  text-align: center;
}
.paragraph1{
  padding: 60px 0;
  line-height: 30px;
}
.paragraph2{
  padding-bottom: 10px;
} 
</style>