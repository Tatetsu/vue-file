<template>
  <div class="main">
    <div class="main_bg" style="position: relative">
      <h2
        style="
          font-size: 1.8em;
          transform: rotate(-5deg);
          text-align: left;
          padding-left: 1rem;
          margin-bottom: 0;
        "
      >
        しせつからのお便り
      </h2>
      <div class="calender">
        <img
          src="../assets/calender.png"
          alt=""
          style="width: 65px; position: absolute; top: 0; right: 10px"
        />
        <p
          style="
            color: #fff;
            position: absolute;
            top: 0;
            right: 15px;
            padding: 0;
            margin: 0;
          "
        >
          2022年
          <br style="border-bottom: 1px solid #fff" />
          <span style="font-size: 2em">4</span>月
        </p>
      </div>
      <div
        class="user_wright"
        style="
          display: flex;
          flex-direction: row;
          align-content: flex-start;
          align-items: flex-start;
          padding-left: 1rem;
        "
      >
        <div class="user_information">
          <div class="user_name">
            <p><input type="text" style="border-radius: 2em" /></p>
          </div>
          <div class="user_text">
            <textarea name="" id="" cols="20" rows="5"></textarea>
          </div>
        </div>
        <div class="user_img">
          <img
            src="../assets/4月.png"
            alt=""
            style="width: 100%; border-radius: 50%; height: 228px"
          />
        </div>
      </div>
      <div class="bg_img" style="display: flex; justify-content: space-around">
        <div class="user_img_bottom" style="height: 250px">
          <img
            src="../assets/4月.png"
            alt=""
            style="border-radius: 40% 3%; width: 45%; height: 100%"
          />
          <img
            src="../assets/4月.png"
            alt=""
            style="border-radius: 50%; width: 45%; height: 100%"
          />
        </div>
      </div>
      <div class="user_comment" style="position: relative; margin-top: 2rem">
        <h3
          style="
            position: absolute;
            top: -15px;
            right: calc(100% - 75%);
            margin: 0 auto;
            border-radius: 1rem;
            padding: 1% 5%;
            background-color: blue;
            font-size: 1em;
            color: #fff;
          "
        >
          施設からのコメント
        </h3>
        <div class="user_comment_input" style="margin-bottom: 2rem;">
          <textarea name="" id="" cols="40" rows="5" style="padding: 5%"></textarea>
        </div>
      </div>
    </div>
    <div class="download">
      <button>ダウンロード</button>
    </div>
  </div>
</template>

<script>
export default {
  name: "NewLetters",
  props: {},
};
</script>

<style scoped>
img {
  width: 100%;
}
.main {
  /* height: 100vh; */
  background-color: bisque;
  display: flex;
  align-items: center;
  flex-direction: column;
  justify-content: center;
}
</style>
