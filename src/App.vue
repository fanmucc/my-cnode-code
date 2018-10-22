<template>
  <div id="app">
    <header>
      <Header></Header>
    </header>
    <main>
      <router-view name="SlideBar"></router-view>
      <router-view name='main'></router-view>
      
    </main>
  </div>
</template>

<script>
import Header from '@/components/Header'
import PostList from '@/components/PostList'
export default {
  name: 'App',
  components: {
    Header,
    PostList,
  }
}
</script>

<style>
* {
  margin: 0;
  padding: 0;
}
#app {
    display: grid;
    grid-template-rows: 5% 90% 5%;
    background: #e1e1e1;
}
</style>
