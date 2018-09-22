<template>
  <div id="app">
    <h1>{{ title }}</h1>
    <navbar />
    <nav>
      <ul>
            <li>
                <a href="">Home</a>
                <a href="">About</a>
                <a href="">Contact</a>
            </li>
        </ul>
    </nav>
  </div>
</template>

<script>
import Navbar from './Navbar'

export default {
  name: 'app',
  components: {
    Navbar
  },
  data () {
    return {
      title: 'My first Vue app :)'
    }
  }
}
</script>

<style>
h1{
  color: #444;
  font-weight: normal;
  text-align: center;
}
</style>
