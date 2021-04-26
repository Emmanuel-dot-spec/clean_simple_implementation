<template>
  <div class="navbar">
    <nav>
      <div>
        <img src="../assets/logo-nav.svg" alt="" />
      </div>
      <div class="links">
        <!-- <a href="#">Home</a>
        <a href="#">Categories</a>
        <a href="#">FAQ</a>
        <a href="#">Become an Agent</a> -->
        <router-link class="a-home" :to="{ path: '/' }">Home</router-link>
        <router-link :to="{ path: '/' }">Blog</router-link>
        <router-link :to="{ path: '/' }">Features</router-link>
        <router-link :to="{ path: '/' }">Pricing</router-link>
        <router-link :to="{ path: '/' }">documentation</router-link>
      </div>

      <div class="icons-nav">
        <img class="imoticons" src="../assets/fb.svg" alt="" />
        <img class="imoticons" src="../assets/direction.svg" alt="" />
        <img class="imoticons" src="../assets/twitter.svg" alt="" />
        <img class="imoticons" src="../assets/m.svg" alt="" />
      </div>

      <div class="buttons">
        <router-link :to="{ path: '/' }"
          ><button class="sign-up">Get Started</button></router-link
        >
      </div>
    </nav>
  </div>
</template>

<script>
export default {};
</script>

<style scoped>
nav {
  display: flex;
  align-items: center;
  justify-content: space-between;
  background: #ffffff;
  padding: 5px 50px;
  width: 100%;
  padding-bottom: 20px;
}
.links {
  margin-left: -600px;
}
.links a {
  font-family: Quicksand;
  font-style: normal;
  font-weight: 500;
  font-size: 12px;
  line-height: 15px;
  /* identical to box height */

  /* align-items: center;
  text-align: center; */
  letter-spacing: 0.05em;
  text-transform: capitalize;
  color: #697ca6;
  text-shadow: 0px 0px 5px #e6e6e6;
  margin-left: 42px;
}
.a-home {
  font-weight: bold !important;
  /* identical to box height */
  color: #5e81fe !important;
}

.buttons .sign-up {
  margin-left: 20px;
  padding: 10px 20px;
  cursor: pointer;
  /* added */
  height: 43px;
  background: #d2e1ff;
  border-radius: 2px;
  border: 0.1px solid #d2e1ff;
  /* text */
  font-family: Quicksand;
  font-style: normal;
  font-weight: bold;
  font-size: 13px;
  line-height: 16px;
  /* identical to box height */
  align-items: center;
  text-align: center;
  color: #3a79ff;
}
.icons-nav {
  margin-right: -600px;
}
.imoticons {
  margin-left: 34px;
}
</style>
