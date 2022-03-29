<template>
  <div class="main">
    <router-link to="/">Topページ</router-link>
    <h1>ログイン</h1>
    <div class="login">
      <form action="post">
        <input type="text" placeholder="sample@mail.com" />
        <input type="text" placeholder="password" />
        <button type="submit">ログイン</button>
      </form>
      <div class="password_reset">
        <p><router-link to="/">パスワードを忘れた方はこちら</router-link></p>
      </div>
    </div>
  </div>
</template>

<script>
export default {
  name: "SignIn",
  props: {},
};
</script>

<style scoped>
a {
  text-decoration: none;
  color: #40b983;
}
a:hover {
  color: blue;
}
.main {
  display: flex;
  flex-direction: column;
  align-items: center;
  justify-content: center;
  height: 100vh;
}
.login {
  max-width: 450px;
  margin: 0 auto;
}
.login form {
  display: flex;
  flex-direction: column;
}
.login form input {
  margin: 1rem auto;
  width: 300px;
  max-width: 450px;
  min-width: 200px;
}
.login form button {
  width: 150px;
  margin: 1rem auto;
}
</style>
