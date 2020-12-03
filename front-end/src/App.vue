<template>
<div id="app">
  <div class="header">
    <router-link to="/">
      <div class="logo">
        <img src="/hammer.png" width="110" height="100" />
      </div>
    </router-link>
    <div class="title">
      <h1>Pointless Auction House</h1>
    </div>
  </div>
  <div class="content">
    <router-view />
  </div>
  <div class="footer">
    <router-link to="/admin">Listing Page</router-link>
    <p><a href="https://github.com/Chris-Mero/creative4">Chris and McKay's Github</a></p>
  </div>
</div>
</template>

<style>
html {
  box-sizing: border-box;
}

body {
  font-family: 'Montserrat', sans-serif;
  font-size: 16px;
  background: #fff;
  padding: 0px;
  margin: 0px;
}

/* Header */
.header {
  display: flex;
  width: 100%;
  padding: 10px 100px 0px 100px;
  background-color: #aa8f79;
  color: white;
}

.title {
  margin-top: 5px;
}

.title h1 {
  font-size: 30px;
}

.content {
  padding: 20px 100px;
  min-height: 500px;
}

/* Footer */
.footer {
  position: fixed;
  bottom: 0;
  width: 100%;
  height: 50px;
  padding: 20px 100px 20px 100px;
  margin-top: 30px;
  background: #aa8f79;
  font-size: 12px;
  text-align: center;
}

.footer a {
  color: #000;
}

h1 {
  font-size: 20px;
}

h2 {
  font-size: 14px;
}
</style>
