<template>
    <div>
        <NavBar></NavBar>
        <main>
            <div class="container">
                <router-view></router-view>
            </div>
        </main>
        <FooterComponent />
    </div>
</template>

<script>
import NavBar from './components/NavBar';
import FooterComponent from './components/FooterComponent';

export default {
  name: 'App',
  components: {
    NavBar,
    FooterComponent,
  },
}
</script>

<style lang="scss">
    @import '~bootstrap/scss/bootstrap';
</style>
