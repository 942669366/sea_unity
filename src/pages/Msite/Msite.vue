<template>
	 <section class="msite">
		<!--首页头部-->
    <HeaderTop title="海团">
    <span class="header_search" slot="left">
      <i class = "iconfont icon-sousuo"></i>
    </span>
      <span class="header_login" slot="right">
        <span class="header_login_text">登陆|注册</span>
      </span>
		</HeaderTop>
		<!--首页导航-->

      <div class="banner">
      	<div class="swiper-container" style="height:150px">
          <div class="swiper-wrapper" style="margin-top:-8px">
            <div class="swiper-slide">
              <a href="javajcript:;" >
                <img src="../../../src/pages/Msite/imges/timg1.jpg">
              </a>
            </div>
            <div class="swiper-slide">
              <a href="javajcript:;" >
                <img src="../../../src/pages/Msite/imges/timg3.jpg">
              </a>
                
            </div>
				  </div>
				<!-- 如果需要分页器 -->
				  <div class="swiper-pagination"></div>


				
			  </div>
    </div>
		<nav class="msite_nav">
			<div class="swiper-container">
				<div class="swiper-wrapper">
					<div class="swiper-slide">
            <ul class="menu">
              <li>              
                <a href="#"></a> 
                <h2>美食</h2>
              </li>
              <li>
                <a href="#"></a>
                <h2>卖场便利</h2>
              </li>
              <li>
                <a href="#"></a>
                <h2>水果</h2>
              </li>
              <li>
                <a href="#"></a>
                <h2>甜品饮品</h2>
              </li>

              <li>
                <a href="#"></a>
                <h2>甜品饮品</h2>
              </li>
            </ul>
            <ul class="menu1">
              <li>  
                <a href="#"></a>
                <h2>好店</h2>
              </li>
              <li>
                <a href="#"></a>
                <h2>送药上门</h2>
              </li>
              <li>
                <a href="#"></a>
                <h2>惠吃</h2>
              </li>
              <li>
                <a href="#"></a>
                <h2>蜂鸟即配</h2>
              </li>
              <li>
                <a href="#"></a>
                <h2>甜品饮品</h2>
              </li>
            </ul>
					</div>
					<div class="swiper-slide">
              <ul class="menu">
              <li>              
                <a href="#"></a> 
                <h2>美食</h2>
              </li>
              <li>
                <a href="#"></a>
                <h2>卖场便利</h2>
              </li>
              <li>
                <a href="#"></a>
                <h2>水果</h2>
              </li>
              <li>
                <a href="#"></a>
                <h2>甜品饮品</h2>
              </li>

              <li>
                <a href="#"></a>
                <h2>甜品饮品</h2>
              </li>
            </ul>
            <ul class="menu1">
              <li>  
                <a href="#"></a>
                <h2>好店</h2>
              </li>
              <li>
                <a href="#"></a>
                <h2>送药上门</h2>
              </li>
              <li>
                <a href="#"></a>
                <h2>惠吃</h2>
              </li>
              <li>
                <a href="#"></a>
                <h2>蜂鸟即配</h2>
              </li>
              <li>
                <a href="#"></a>
                <h2>甜品饮品</h2>
              </li>
            </ul>
            <div>
              <a href="javascript:" class="link_to_food">
                <div class="food_container">
                  <img src="../../../build/logo.png">
                  <span>水果</span>
                </div>
						  </a>
              <a href="javascript:" class="link_to_food">
                <div class="food_container">
                  <img src="../../../build/logo.png">
                  <span>水果</span>
                </div>
						  </a>
              <a href="javascript:" class="link_to_food">
                <div class="food_container">
                  <img src="../../../build/logo.png">
                  <span>水果</span>
                </div>
						  </a>
              <a href="javascript:" class="link_to_food">
                <div class="food_container">
                  <img src="../../../build/logo.png">
                  <span>水果</span>
                </div>
						  </a>
              <a href="javascript:" class="link_to_food">
                <div class="food_container">
                  <img src="../../../build/logo.png">
                  <span>水果</span>
                </div>
						  </a>
            </div>
              
					</div>
				</div>
				
				<!-- 如果需要分页器 -->
				<div class="swiper-pagination"></div>

        <div class="swiper-scrollbar">
        </div>
				
			</div>
		</nav>
    <div class="mht_list">
      <div class="move">电影</div>
      <div class="hotel">酒店</div>
      <div class="tickets">火车票</div>
    </div>
    <div class="foot_list">
      <ul>
        <li class="store_li">
          <div class="store_logo">
            <img src="../../../build/logo.png"/>
          </div>
          <div class="store_massage">
            <div class="store_title">
              <h4 class="store_name">
                百位果园百位果园
              </h4>
            </div>
            <div>
              <div class="grage">
                <img src="../../../src/Star/images/star24_on@2x.png"/>
                <img src="../../../src/Star/images/star24_on@2x.png"/>
                <img src="../../../src/Star/images/star24_on@2x.png"/>
                <img src="../../../src/Star/images/star24_on@2x.png"/>
                <img src="../../../src/Star/images/star24_half@2x.png"/>
              </div>
              <div class="sales">
                <span>月销量：<span style="color:#02a774">1w+</span></span>
              </div>
            </div>
          </div>
        </li>
      
      </ul>
    </div>
	</section> 
</template>

<script>
  import HeaderTop from '../../components/HeaderTop/HeaderTop.vue'
	import Swiper from 'swiper'
	import 'swiper/dist/css/swiper.min.css'
	export default {
		mounted() {
			new Swiper('.swiper-container',{
				loop:true,
				pagination:{
					el:'.swiper-pagination',
				},
			})
		},
		components:{
			HeaderTop
		}
	}
</script>


<style lang="stylus" rel="stylesheet/stylus">
   @import "../../common/stylus/mixins.styl"
  *
    padding 0
    margin 0
  .banner
    width 100%
    height 100px
    margin-top 46px
    a img
      width 100%
      height 150px
  .swiper-wrapper
    width 100%
    height 160px
    margin-top 46px 
    .swiper-slide
      width 100%
      height 90%
      margin-top 8px
      background-color c2c2c2
      .menu
        width 90%
        height 50%
        margin 0 0 0 5%
        // background-color red
        li
          width 18%
          height 3.5rem
          float left
          margin 1.2% 0 0 1.6%
          text-align center
          // background-color blue
          h2
            height 1.3rem
            font 12px/12px "Microsoft Yahei"
            color #666
          a
            display block
            width 2.8rem
            height 2.5rem
            margin-left 10%
            background-color red
            background:url(../../../src/Star/images/1.png) 0.2rem -2.3rem no-repeat
            background-size: 2.6rem 38.4rem
        li:nth-child(2) a
          background-position 0.2rem -4.65rem
        
        li:nth-child(3) a
          background-position 0.1rem -6.9rem
        
        li:nth-child(4) a
          background-position: left -9.2rem
        
        li:nth-child(5) a
          background-position left -11.6rem
      .menu1
        width 90%
        height 50%
        margin 0 0 0 5%
        // background-color red
        li
          width 18%
          height 3.5rem
          float left
          margin 1.2% 0 0 1.6%
          text-align center
          // background-color blue
          h2
            height 1.3rem
            font 11px/11px "Microsoft Yahei"
            color #666
          a
            display block
            width 2.8rem
            height 2.5rem
            margin-left 10%
            background-color red
            background:url(../../../src/Star/images/1.png) 0.2rem -14rem no-repeat
            background-size: 2.6rem 38.4rem
        li:nth-child(2) a
          background-position left -16.35rem
        
        li:nth-child(3) a
          background-position left -19rem
        li:nth-child(4) a
          background-position 0.2rem -21.65rem
        li:nth-child(5) a
          background-position 0.2rem -24rem
      .link_to_food
        float left
        margin-left 6.8%
        margin-top 10px
        .food_container
          float left
          height 45px
          width 45px
          text-align center
          font-size 12px
          background-color:blue
          span
            text-align center
            float left
            font 11px/11px "Microsoft Yahei"
          img 
            width 25px
            height 25px
.mht_list
  width 100%
  background-color red
  .move
    font-size 10px
    margin-left 10px
    float left
    text-align center
    line-height 25px
    height 25px
    width  80px
    background-color #efefef
  .hotel
    font-size 10px
    margin-left 10px
    float left
    text-align center
    height 25px
    line-height 25px
    width  80px
    background-color #efefef
  .tickets
    font-size 10px
    margin-left 10px
    float left
    text-align center
    height 25px
    line-height 25px
    width  80px
    background-color #efefef
.store_li
  float left
  width 100%
  height 50px
  margin-top 5px
  .store_logo
    text-align center
    line-height 50px
    float left
    width 50px
    height 50px
    img
      width 40px
      height 40px
  .store_massage
    margin-left 1px
    width 238px
    height 50px
    float left
    .store_title
      width 130px
      height 20px
      line-height 20px
      margin-left 1px
      margin-top 3.5px
      .store_name
        width 110px
        height 20px
        color #666;
        font 18px/18px "Microsoft Yahei"
        overflow hidden
        white-space nowrap
        text-overflow ellipsis
    a
      text-decoration none 
      font-size 20px
      color #8c8c8c
    .grage
      height 20px
      width 100px
      margin-top 5px
      img
        line-height 15px
        margin-left 1px
        float left
        width 12px
        height 12px
    .sales
      font-size 10px 
      line-height 20px
      width 80px
      height 20px
      margin-left 110px
      margin-top -20px
      float left
      
</style>
