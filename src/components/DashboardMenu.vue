<template>
  <div class="main">
    <div class="dashboard">
      <div class="new_date">
        <button >新規作成</button>
      </div>
      <div class="date_change">
        <button >登録変更</button>
      </div>

    </div>
  </div>
</template>

<script>
export default {
  name: "DashboardMenu",
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
