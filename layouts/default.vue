<template>
<!-- コンポーネントの基本となるプロパティ 
ここに書いた内容が、ページに表示される-->

  <div>
    <!-- 各ページ異なるNuxtコンポーネントを表示している -->
    <nuxt />
  </div>
</template>

// 各ページに共通するstyleは、default.vueに書くとよい
//これは、styleが明示的に示されていない全てのコンポーネントに適応される

<style>
html {
 font-family: 'Merriweather', serif;
  font-size: 128px;
  word-spacing: 1px;
  -ms-text-size-adjust: 100%;
  -webkit-text-size-adjust: 100%;
  -moz-osx-font-smoothing: grayscale;
  -webkit-font-smoothing: antialiased;
  box-sizing: border-box;
}
*,
*:before,
*:after {
  box-sizing: border-box;
  margin: 0;
}

.button--green {
  display: inline-block;
  border-radius: 4px;
  border: 1px solid #3b8070;
  color: #3b8070;
  text-decoration: none;
  padding: 10px 30px;
}
.button--green:hover {
  color: #fff;
  background-color: #3b8070;
}
.button--grey {
  display: inline-block;
  border-radius: 4px;
  border: 1px solid #35495e;
  color: #35495e;
  text-decoration: none;
  padding: 10px 30px;
  margin-left: 15px;
}
.button--grey:hover {
  color: #fff;
  background-color: #35495e;
}
</style>