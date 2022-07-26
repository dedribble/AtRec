<template>
  <nav>
      <div class="logo"><a href="#">AtRec</a></div>
  </nav>
  <router-view/>
</template>

<style>
:root {
  --background: #283044;
  --logo-color: #ffffff;
  --text-color: #EBF5EE;
}
@font-face {
    font-family: 'bavroregular';
    src: url('./assets/font/BAVRO/webfont/bavro-regular-webfont.eot');
    src: url('./assets/font/BAVRO/webfont/bavro-regular-webfont.eot') format('embedded-opentype'),
         url('./assets/font/BAVRO/webfont/bavro-regular-webfont.woff2') format('woff2'),
         url('./assets/font/BAVRO/webfont/bavro-regular-webfont.woff') format('woff'),
         url('./assets/font/BAVRO/webfont/bavro-regular-webfont.ttf') format('truetype'),
         url('./assets/font/BAVRO/webfont/bavro-regular-webfont.svg') format('svg');
    font-weight: normal;
    font-style: normal;
}
@import url('https://fonts.googleapis.com/css2?family=Poppins:ital,wght@0,100;0,200;0,300;0,400;0,500;0,600;0,700;0,800;0,900;1,100;1,200;1,300;1,400;1,500;1,600;1,700;1,800;1,900&family=Roboto+Mono:ital,wght@0,100;0,200;0,300;0,400;0,500;0,600;0,700;1,100;1,200;1,300;1,400;1,500;1,600;1,700&family=Roboto:ital,wght@0,100;0,300;0,400;0,500;0,700;0,900;1,100;1,300;1,400;1,500;1,700;1,900&display=swap');
* {
  padding: 0px;
  margin:0px;
  box-sizing: border-box;
}
html{
  font-size: 16px;
}
body{
  width: 100%;
  min-height: 100vh;
  background: var(--background);
  display: flex;
  justify-content: center;
  padding: 0 10px;
}
nav {
  display: flex;
  align-items: center;
  justify-content: center;
  width: 100vw;
  height: 80px;
  padding: 30px;
}
nav .logo {
  display: flex;
  align-items: center;
  justify-content: center;
}
nav .logo a {
  display: flex;
  align-items: center;
  justify-content: center;
  text-decoration: none;
  font-family: 'bavroregular';
  font-size: 2.5rem;
  font-weight: 300;
  color: var(--logo-color);
}
</style>