<template>
  <div id="Index">
    <div class="wrapper-body-content">
      <div class="content">
        <aside>
          <div class="content-top">
            <div class="title">
              <h2>Home</h2>
            </div>
            <div class="portrait">
              <img src="../static/image/logo.jpg" />
            </div>
            <div class="name"><span>旭阳前端</span></div>
            <div class="tag"><span>Keep it up</span></div>
          </div>

          <nav>
            <ul>
              <li>
                <div class="icon"><img src="../static/image/home.png" /></div>
                <div class="name">小太阳前端</div>
              </li>
              <li>
                <div class="icon">
                  <img src="../static/image/wendnag.png" />
                </div>
                <div class="name">文章归档</div>
              </li>
              <li>
                <div class="icon">
                  <img src="../static/image/jianjie_1.png" />
                </div>
                <div class="name">前端简历</div>
              </li>
              <li>
                <div class="icon">
                  <img src="../static/image/jianjie.png" />
                </div>
                <div class="name">前端作品</div>
              </li>
              <li>
                <div class="icon">
                  <img src="../static/image/daohang.png" />
                </div>
                <div class="name">前端导航</div>
              </li>
              <li>
                <div class="icon"><img src="../static/image/qita_1.png" /></div>
                <div class="name">业余其他</div>
              </li>
              <li>
                <div class="icon">
                  <img src="../static/image/lianjie_1.png" />
                </div>
                <div class="name">友情链接</div>
              </li>
            </ul>
          </nav>
        </aside>
        <main>
          <div class="wrapper-head">
            <div class="content-query">
              <div class="icon"></div>
              <a-input placeholder="Enter your search re" class="Input" />
            </div>
            <div class="wrapper-icon">
              <div class="mr-15 icon icon1"></div>
              <div class="icon icon2"></div>
            </div>
          </div>
          <div class="wrapper-body">
            <div class="img">
                  <img src="../static/image/xin.webp" />
            </div>
            <div class="info">
              <h1>欢迎来到旭阳的小屋！</h1>
              <h2>大干一场吧！！！</h2>
            </div>
          </div>
          <div class="wrapper-content">
            <div class="item" v-for="i in 3">
              <div class="title">hello word</div>
              <div class="subtitle">
                <div class="subtitle-item">
                  <div class="icon icon1"></div>
                  <div class="text">发表于：2022-4-16 |</div>
                </div>
                <div class="subtitle-item">
                  <div class="icon icon2"></div>
                  <div class="text">本文字数： 2k |</div>
                </div>
                <div class="subtitle-item">
                  <div class="icon icon3"></div>
                  <div class="text">阅读时长：2分钟</div>
                </div>
              </div>
              <div class="textarea">
《进击的巨人》（进撃の巨人），是日本漫画家谏山创创作的少年漫画作品，于2009年在讲谈社旗下的漫画杂志《别册少年Magazine》上开始连载，至2021年4月9日完结。全139话。 [66] 该作品曾获2011年“这本漫画真厉害！”男性榜第1名、“讲谈社漫画赏少年部门赏”等奖项 。2012年12月，该作正式宣布TV动画化，2013年4月6日，由WIT STUDIO改编的同名电视动画正式开始放送。 截止至2019年12月25日，单行本（含电子版）累计全球发行量突破1亿册。 [1]
              </div>
              <div class="operation">
                <div class="full-text"><span class="left">阅读全文</span><span class="right">》</span></div>
              </div>
            </div>
          </div>
        </main>
      </div>
      <footer><span>黑ICP备2021002448号-1</span></footer>
    </div>
  </div>
</template>

<script lang="ts">
import Vue from "vue";
import "./index.less";
export default Vue.extend({
  name: "IndexPage",
  created(){
  }
});
</script>
<style lang="less" scoped>
</style>