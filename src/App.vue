<template>
  <div id="app">
    <header>
      <nav>
        <ul>
          <li class='nav-item'>
            <img class='logo' src='./assets/build-a-bot-logo.png'>Build-a-bot
          </li>
        </ul>
      </nav>
    </header>
    <HomePage />
  </div>
</template>

<script>
import HomePage from './components/HomePage.vue';

export default {
  name: 'app',
  components: {
    HomePage,
  },
};
</script>

<style>
body{
  background: #141E30;  /* fallback for old browsers */
  background: -webkit-linear-gradient(to right, #243B55, #141E30);  /* Chrome 10-25, Safari 5.1-6 */
  background: linear-gradient(to right, #243B55, #141E30); /* W3C, IE 10+/ Edge, Firefox 16+, Chrome 26+, Opera 12+, Safari 7+ */

}
#app {
  font-family: 'Avenir', Helvetica, Arial, sans-serif;
  padding: 20px;
  width:80%;
  margin :0 auto;
  text-align: center;
  color: #2c3e50;
}
header {
  background-color: #999;
  margin: 0 auto;
}
ul {
  padding: 3px;
  display: flex;
}
.nav-item {
  display: inline-block;
  padding: 5px 10px;
  font-size: 22px;
  border-right: 1px solid #bbb;
}
.logo {
  vertical-align: middle;
  height: 30px;
}
</style>
