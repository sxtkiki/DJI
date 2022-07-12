<template>
  <div>
    <nav class="nav">
      <div class="nav-container">
        <div class="product-title">
          <a href="#">DJI Mini 3 Pro</a>
        </div>
        <ul class="nav-right">
          <li>
            <a
              
              
              href="#"
              >技术参数</a>
          </li>
          <li>
            <a
              href="#"
              
              >机型比较</a>
          </li>
          <li>
            <a
              href="#"
             
              >视频</a>
          </li>
          <li>
            <a
              href="#"
             
              >下载</a>
          </li>
          <li>
            <a
              href="#"
              
              >常见问题</a>
          </li>
          <li>
            <a href="#">
              <img style="width:20px;line-height:40px;" src="../assets/login.png" alt="">
            </a>
          </li>
        </ul>
      </div>
    </nav>
  </div>
</template>

<script>
export default {
  
};
</script>

<style lang="scss" scoped>
* {
  margin: 0;
  padding: 0;
  text-decoration: none;
  list-style: none;
  user-select: none;
}
.nav {
  background-color: rgba(35,37,38,.9);
  width: 100%;
  height: 100%;
  // position: fixed;
}
.nav-container {
  height: 64px;
    width: 1200px;
    display: flex;
    margin-left: auto;
    margin-right: auto;
    align-items: center;
    justify-content: space-between;
}
.product-title {
    font-size: 14px;
    line-height: 64px;
    font-weight: 400;
    cursor: pointer;
}
.product-title a {
  color: white;
}
.nav-right{
    flex: 1;
    display: flex;
    align-items: center;
    justify-content: flex-end;
    text-transform: none;
}
.nav-right li{
  height: 100%;
  line-height: 64px;
  padding: 0 16px;
}
.nav-right a {
  color: white;
}
</style>