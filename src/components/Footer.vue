<!--
 * @Author: error: git config user.name && git config user.email & please set dead value or install git
 * @Date: 2022-02-12 22:20:06
 * @LastEditors: error: git config user.name && git config user.email & please set dead value or install git
 * @LastEditTime: 2022-09-01 22:42:35
 * @FilePath: \shop\src\components\Footer.vue
 * @Description: 这是默认设置,请设置`customMade`, 打开koroFileHeader查看配置 进行设置: https://github.com/OBKoro1/koro1FileHeader/wiki/%E9%85%8D%E7%BD%AE
-->
<!--
 * @Author: error: git config user.name && git config user.email & please set dead value or install git
 * @Date: 2022-02-12 22:20:06
 * @LastEditors: error: git config user.name && git config user.email & please set dead value or install git
 * @LastEditTime: 2022-09-01 22:37:09
 * @FilePath: \shop\src\components\Footer.vue
 * @Description: 这是默认设置,请设置`customMade`, 打开koroFileHeader查看配置 进行设置: https://github.com/OBKoro1/koro1FileHeader/wiki/%E9%85%8D%E7%BD%AE
-->
<template>
  <div class="footer ">
    <div class="footer-hd ">
      <p>
        <!--<a href="http://www.mingrisoft.com/" target="_blank">明日科技</a>
        <b>|</b>-->
        <a href="javascript:void(0)" @click="show">商城首页</a>
        <b>|</b>
        <a href="javascript:void(0)">支付宝</a>
        <b>|</b>
        <a href="javascript:void(0)">物流</a>
      </p>
    </div>
    <div class="footer-bd ">
      <p>
        <!--<a href="http://www.mingrisoft.com/Index/ServiceCenter/aboutus.html" target="_blank">关于明日 </a>-->
        <a href="javascript:void(0)">合作伙伴 </a>
        <a href="javascript:void(0)">联系我们 </a>
        <a href="javascript:void(0)">网站地图 </a>
        <em>© <!--2016-2025 mingrisoft.com--> 版权所有</em>
      </p>
    </div>
  </div>
</template>
<script>
  export default {
    //name: 'bottom',
    methods: {
      show: function () {
        this.$router.push({name:'home'});//跳转到主页
      }
    }
  }
</script>
