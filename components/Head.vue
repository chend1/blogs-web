<script setup></script>

<template>
  <div class="head">
    <div class="logo">
      <nuxt-link to="/">LOGO</nuxt-link>
    </div>
    <nav>
      <ul>
        <li>
          <nuxt-link to="/home">首页</nuxt-link>
        </li>
        <li>
          <nuxt-link to="/about">关于</nuxt-link>
        </li>
        <li>
          <nuxt-link to="/article">文章</nuxt-link>
        </li>
      </ul>
    </nav>
  </div>
</template>

<style lang="less" scoped>
.head {
  position: fixed;
  top: 0;
  left: 0;
  width: 100%;
  height: 60px;
  box-sizing: border-box;
  padding: 0 20px;
  display: flex;
  align-items: center;
  justify-content: space-between;
  background-color: rgba(0, 0, 0, 0.1);
  nav {
    ul {
      display: flex;
      align-items: center;
      li {
        margin-left: 20px;
      }
    }
  }
}
</style>
