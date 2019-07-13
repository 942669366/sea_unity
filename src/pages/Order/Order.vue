<template>
  <section class="order">
    <HeaderTop title="订单列表"/>
      <section class="order_no_login">
        <img src="../../../build/logo.png" width="30px">
        <h3>登录后查看外卖订单</h3>
      <router-link to="/login" class="profile-link">
        <button>立即登陆</button>
      </router-link>
      </section>
  </section>
</template>

<script>
	import HeaderTop from '../../components/HeaderTop/HeaderTop.vue'
	export default {
		components:{
			HeaderTop
		}
	}
</script>

<style lang="stylus" rel="stylesheet/stylus">
 @import "../../common/stylus/mixins.styl"
  .header
      background-color #02a774
      position fixed
      z-index 100
      left 0
      top 0
      width 100%
      height 45px
  .order  //订单
    width 100%
    .order_no_login
      padding-top 140px
      width 60%
      margin 0 auto
      text-align center
      >img
        display block
        width 100%
        height 30%
      >h3
        padding 10px 0
        font-size 17px
        color #6a6a6a
      >button
        display inline-block
        background #02a774
        font-size 14px
        color #fff
        border 0
        outline none
        border-radius 5px
        padding 10px 20px
</style>