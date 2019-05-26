<template>
	<div class='home'>
		<home-header></home-header>

		<!--<home-swiper :swiperList='swiperList'></home-swiper>-->

		<!--<home-icons :iconsList='iconsList'></home-icons>-->

		<!--<home-location></home-location>-->
		<!--<home-activity></home-activity>-->

		<!--<home-hot :hotList='hotList'></home-hot>-->

		<!--<home-like :likeList='likeList'></home-like>-->

		<!--<home-vacation :vacationList='vacationList'></home-vacation>-->
	</div>
</template>
<script>
  import HomeHeader from './pages/Header'
  export default {
    components:{
      HomeHeader
    }
  }
</script>
<style scoped>
.home{
	background: #f5f5f5;
}
</style>
