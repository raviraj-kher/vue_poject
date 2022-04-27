<template>
  <img alt="Vue logo" src="./assets/logo.png">
  <!-- <HelloWorld msg="Welcome to Your Vue.js App"/> -->
  <index />
  <studentData name="Raviraj"/>
  <teacherData name="Dharmesh"/>
  <!-- <formElement /> -->
</template>

<script>
import index from './components/index.vue'
import studentData from './components/student.vue'
import teacherData from './components/teacher.vue'
// import formElement from './components/formElement.vue'
// import HelloWorld from './components/HelloWorld.vue'
// import Home from './components/index.vue'

export default {
  name: 'App',
  components: {
    // HelloWorld
    index,
    studentData,
    teacherData,
    // formElement
  }
}
</script>
