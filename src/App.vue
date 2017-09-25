<template>
  <div id="app">
    <!-- <router-view></router-view> -->
     <!-- 顶部导航 -->
    <div class="header">
        <div class="headBox">
          <img class="scan" src="/static/img/saoyisao.png" alt="">
          <div class="nav">
            <div class="nav_a">
                <a href="###" class="select">推荐</a>
                <a href="###">食材</a>
                <a href="###">分类</a>
            </div>
          </div>
          <img class="search" src="/static/img/sousuo.png" alt="">
        </div>
    </div>

    <!-- 轮播图部分 -->
    <div class="banner">
        <ul class="bar">
          <li><a href="###"><img src="/static/img/shouye_bar1.jpg" alt=""></a></li>
         <li><a href="###"><img src="/static/img/shouye_bar2.jpg" alt=""></a></li>
         <li><a href="###"><img src="/static/img/shouye_bar3.jpg" alt=""></a></li>
         <li><a href="###"><img src="/static/img/shouye_bar4.jpg" alt=""></a></li>
        </ul>
        <div class="bar_span">
          <span></span>
          <span></span>
          <span></span>
          <span></span>
        </div>
    </div>       

    <!-- 内容部分 -->
    <div class="content">
      <div class="con_seach">
          <img src="../static/img/sousuo2.png" alt="">
          <span>输入菜名或食材搜索</span>
      </div>
      <div class="con_sel">
          <div class="sel_box">
              <a href="###">
                  <img src="../static/img/shouye_xinshou.png" alt="">
                  <span>新手入门</span>
              </a>
              <a href="###">
                  <img src="../static/img/shouye_shicai.png" alt="">
                  <span>食材搭配</span>
              </a>
              <a href="###">
                  <img src="../static/img/shouye_changjing.png" alt="">
                  <span>场景菜谱</span>
              </a>
              <a href="###">
                  <img src="../static/img/shouye_zhibo.png" alt="">
                  <span>美食直播</span>
              </a>
          </div>
          <div class="sel_ul">
            <ul>
              <li></li>
            </ul>
          </div>
      </div>

    </div>

    <!-- 底部导航栏部分 -->
    <div class="footer">
        <ul>
          <li><a href="###"><img src="/static/img/fr_shipu_ok.png" alt=""><span>食谱</span></a></li>
          <li><a href="###"><img src="/static/img/fr_lehuo.png" alt=""><span>乐活</span></a></li>
          <li><a href="###"><img src="/static/img/fr_shequ.png" alt=""><span>社区</span></a></li>
          <li><a href="###"><img src="/static/img/fr_wode.png" alt=""><span>我的</span></a></li>
        </ul>
    </div>
  </div>
</template>

<script>
export default {
  name: 'app'
}
</script>

<style>
  @import "../static/css/shouye.css";
</style>
