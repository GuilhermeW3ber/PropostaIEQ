<template>
  <div>
    <Navbar/>
    <Hero/>
    <OverView/>
    
    <Deliverables/>
    <Concept/>
    <Estimate/>
    <Contact/>
    <Whatsapp/>
  </div>
</template>

<script>
import Navbar from '@/components/Navbar.vue'
import Hero from '@/components/Hero.vue'
import OverView from '@/components/OverView.vue'
import Concept from '@/components/Concept.vue'
import Deliverables from '@/components/Deliverables.vue'
import Estimate from '@/components/Estimate.vue'
import Contact from '@/components/Contact.vue'
import Whatsapp from '@/components/Whatsapp.vue'

export default {
  name: 'HelloWorld',
  components: {
    Navbar,
    Hero,
    Concept,
    OverView,
    Deliverables,
    Estimate,
    Contact,
    Whatsapp
  },
  props: {
    msg: String
  }
}
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped>
h3 {
  margin: 40px 0 0;
}
ul {
  list-style-type: none;
  padding: 0;
}
li {
  display: inline-block;
  margin: 0 10px;
}
a {
  color: #42b983;
}
</style>
