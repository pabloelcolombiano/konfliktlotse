<template>
  <main class="container-fluid">
    <Section1></Section1>
    <Section2></Section2>
    <SectionNewsletter></SectionNewsletter>
  </main>
</template>

<script>
import Section1 from '../components/home/Section1'
import Section2 from '../components/home/Section2'
import SectionNewsletter from '../components/home/SectionNewsletter'

export default {
  components: {
    Section1,
    Section2,
    SectionNewsletter
  }
}
</script>

<style>
.container {
  margin: 0 auto;
  min-height: 100vh;
  display: flex;
  justify-content: center;
  align-items: center;
  text-align: center;
}

.title {
  font-family: 'Quicksand', 'Source Sans Pro', -apple-system, BlinkMacSystemFont,
    'Segoe UI', Roboto, 'Helvetica Neue', Arial, sans-serif;
  display: block;
  font-weight: 300;
  font-size: 100px;
  color: #35495e;
  letter-spacing: 1px;
}

.subtitle {
  font-weight: 300;
  font-size: 42px;
  color: #526488;
  word-spacing: 5px;
  padding-bottom: 15px;
}

.links {
  padding-top: 15px;
}
</style>
