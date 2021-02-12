<template>
  <nav class="flex flex-wrap items-center justify-between p-5 bg-blue-200">
    <img src="http://acmelogos.com/images/logo-1.svg" alt="ACME" width="120" />
    <div class="flex md:hidden">
      <button id="hamburger">
        <img class="toggle block" src="https://img.icons8.com/fluent-systems-regular/2x/menu-squared-2.png" width="40" height="40" />
        <img class="toggle hidden" src="https://img.icons8.com/fluent-systems-regular/2x/close-window.png" width="40" height="40" />
      </button>
    </div>
    <div class="toggle hidden md:flex w-full md:w-auto text-right text-bold mt-5 md:mt-0
     border-t-2 border-blue-900 md:border-none">
      <a href="#" class="block md:inline-block text-blue-900 hover:text-blue-500 px-3
       py-3 border-b-2 border-blue-900 md:border-none">Home</a>
      <a href="#" class="block md:inline-block text-blue-900 hover:text-blue-500 px-3
       py-3 border-b-2 border-blue-900 md:border-none">Products</a>
      <a href="https://github.com/wellzey31" class="block md:inline-block text-blue-900
       hover:text-blue-500 px-3 py-3 border-b-2 border-blue-900 md:border-none">
       <ThemifyIcon icon="github"/></a>
      <a href="https://www.linkedin.com/in/brett-wells-uleth/" class="block md:inline-block
       text-blue-900 hover:text-blue-500 px-3 py-3 border-b-2 border-blue-900
        md:border-none"><ThemifyIcon icon="linkedin"/></a>
    </div>
    <a href="#" class="toggle hidden md:flex w-full md:w-auto px-4 py-2 text-right
     bg-blue-900 hover:bg-blue-500 text-white md:rounded">Create Account</a>
 </nav>
</template>

<script>
import ThemifyIcon from 'vue-themify-icons';

export default {
  name: 'Navbar',
  components: {
    ThemifyIcon,
  },
};
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped>
* {
margin: 0;
padding: 0;
-moz-box-sizing: border-box;
box-sizing: border-box;
}
body {
font-family: 'Roboto', sans-serif;
}
h1,h2,h3,h4,h5,h6,a{
  margin:0;
}
 a {
  color: inherit;
 }
 nav {
  top: 0%;
  width: 100%;
  position: fixed;
}
.container {
  padding: 22px;
  margin: 0 auto;
  text-align: center;
  display: flex;
  flex-direction: row;
  justify-content: space-between;
}
.container ul li {
  list-style: none;
  margin: 0 10px;
  display: inline-block;
}
.container ul li a:hover {
  padding: 12px;
  color: #fc0;
}
.container ul li a {
  margin: 8px;
  padding: 10px;
  color: #fff;
  font-size: 1.2em;
  text-decoration: none;
  transition: all 0.3s ease-out;
}
.active {
  border-bottom: 2px solid #d0d7d9;
}
.container p{
margin-bottom: 16px;
color: #fc0;
font-weight: 700;
font-size: 20px;
}

</style>
