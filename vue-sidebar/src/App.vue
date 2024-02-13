<template>
  <Sidebar />
  <div>
    <router-view />
  </div>
</template>

<script>
import Sidebar from './components/Sidebar'


export default {
  name: 'App',
  components: {
    Sidebar
  }
}
</script>

<style>

</style>
