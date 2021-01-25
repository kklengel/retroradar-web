<template>
  <q-layout view="lHh Lpr lFf">
    <q-btn to="/" label="Home" icon="home" outline color="primary" />
    <q-btn to="/blog" label="To my blog" icon="menu_book" outline color="secondary" />
    <q-page-container>
      <router-view />
    </q-page-container>
  </q-layout>
</template>

<script>

export default {
  name: 'MainLayout',
  data () {
    return {
  
    }
  }
}
</script>
