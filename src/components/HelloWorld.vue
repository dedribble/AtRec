<template>
  <div>
    <div class="illu">
      <img src="../assets/robo.gif" alt="Robot Face">
    </div>
    <div class="article">
      <h2>We're glad to have you</h2>
      <p>
        Welcome to AtRec, we can help you manage your event attendance record using face recognition.
      </p>
    </div>
    <!-- Link to Host Registration -->
    <div class="host" id="host">
      <router-link to="/about" class="nav-link">Host an event</router-link>
    </div>
   <!-- Link to event list -->
    <div class="host">
      <router-link to="/about" class="nav-link" id="register">Register for an event</router-link>
    </div>

    <div class="socials" id="socials">
      <div class="box"><a href="#">
        <img src="../assets/twitter.png" alt="Twitter">
      </a></div>
      <div class="box"><a href="#">
        <img src="../assets/instagram.png" alt="Instagram">
      </a></div>
      <div class="box"><a href="#">
        <img src="../assets/facebook.png" alt="Facebook">
      </a></div>
    </div>
    <div class="footer">
      <p>Copyright &copy; Adedamola 2022</p>
    </div>

  </div>
</template>


<style scoped>
:root {
  --background: #283044;
  --logo-color: #ffffff;
  --text-color: #EBF5EE;
  --button-color: #78A1BB;
}
div {
  display: flex;
  flex-direction: column;
  align-items: center;
  justify-content: center;
  margin-top: 10px;
}
div .illu {
  width: 60%;
  height: 60%;
  border-radius: 50%;
  overflow: hidden;
}

div  .illu img {
  width: 100%;
  height: 100%;
}

div .article {
  display: flex;
  align-items: center;
  justify-content: center;
}

div .article h2 {
  font-family: 'Poppins', sans-serif;
  font-size: 1.5rem;
  font-weight: 300;
  color: var(--text-color);
  margin-top: 14px;
  margin-bottom: 6px;
}

div .article p {
  font-family: 'Poppins', sans-serif;
  font-size: 0.85rem;
  font-weight: 300;
  color: var(--text-color);
  text-align: center;
  padding: 0 12px;
}

div .host {
  width: 200px;
  height: 60px;
  display: flex;
  align-items: center;
  justify-content: center;
}

div .host .nav-link {
  width: 100%;
  height: 100%;
  display: flex;
  align-items: center;
  justify-content: center;
  margin-top: 40px;
  margin-bottom: 20px;
  padding: 10px 12px;
  text-decoration: none;
  font-family: 'Poppins', sans-serif;
  font-size: 16px;
  border-radius: 6px;
  border: 1px solid #78A1BB;
  background: #78A1BB;
  color: var(--text-color);
}

div .socials {
  display: flex;
  align-items: center;
  justify-content: center;
  flex-direction: row;
  margin-top: 30px;
}
div .socials .box {
  width: 50px;
  height: 50px;
  background: var(--logo-color);
  border-radius: 50%;
  overflow: hidden;
  margin: 12px;
  display: flex;
  align-items: center;
  justify-content: center;
}
div .socials .box a {
  display: flex;
  align-items: center;
  justify-content: center;
}

div #socials .box a img {
  width: 100%;
  height: 100%;
}

div .footer {
  position: absolute;
  bottom: 0;
  padding: 10px;
  font-family: 'Poppins', sans-serif;
  color: var(--text-color);
}
</style>