<template>
  <header class="App">
    <h1 style="margin-top: 30px;">Best plans AI</h1>
    <nav>
      <router-link to="/WhatToDo">WhatToDo</router-link>
      <router-link to="/WhatToEat">WhatToEat</router-link>
    </nav>
  </header>
  <div class="Views">
    <router-view/>
  </div>
</template>

<style>
#app {
  font-family: Avenir, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  color: #2c3e50;
}
.App{
  text-align: center;
}

.Views{
  width: 85%;
  margin: 0 auto;
}
@media screen and (min-width: 520px) {
  .Views{
    width: 60%;
  }
}
@media screen and (min-width: 800px) {
  .Views{
    width: 40%;
  }
}
@media screen and (min-width: 1200px) {
  .Views{
    width: 30%;
  }
}
@media screen and (min-width: 1500px) {
  .Views{
    width: 25%;
  }
}

nav {
  padding: 30px;
}

nav a {
  font-weight: bold;
  color: #2c3e50;
}

nav a.router-link-exact-active {
  color: #42b983;
}
</style>
