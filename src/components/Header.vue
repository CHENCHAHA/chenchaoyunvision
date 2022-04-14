<template>
  <div>
    <!-- 头部导航栏区域 -->
    <div class="content">
      <!-- logo图标区域 -->
      <div class="logo">
        <router-link to="/index">
          <img
            src="../assets/logo/Visionlogo-bai.png"
            title="Vision·CHENCHAOYUN"
            alt=""
          />
        </router-link>
      </div>
      <!-- 导航分类区域 -->
      <div class="nav">
        <ul>
          <router-link to="/index"><li>图片</li></router-link>
          <router-link to="/index"><li>视频</li></router-link>
          <router-link to="/index"><li>上传</li></router-link>
          <router-link to="/index"><li>注册</li></router-link>
          <router-link to="/index"
            ><li><button>登录</button></li></router-link
          >
        </ul>
      </div>
    </div>
  </div>
</template>

<script>
export default {
  data() {
    return {};
  },
  created() {},
  methods: {},
};
</script>

<style lang="less" scoped>
.content {
  padding: 0 50px;
  display: flex;
  height: 80px;
  background-color: black;
  .logo {
    display: flex;
    align-items: center;
    flex: 1;
    img {
      cursor: pointer;
      width: 100px;
      height: 60px;
    }
  }
  .nav {
    flex: 3;
    ul {
      line-height: 80px;
      display: flex;
      justify-content: flex-end;
      li {
        font-size: 14px;
        margin: 0 20px;
        color: #fff;
        letter-spacing: 2px;
        button {
          cursor: pointer;
          height: 30px;
          border-radius: 10px;
          padding: 0 20px;
        }
        button:hover {
          color: #fff;
          background-color: aqua;
          transition: all 0.5s;
        }
      }
      li:hover {
        color: aqua;
        transition: all 0.2s;
      }
    }
  }
}
</style>