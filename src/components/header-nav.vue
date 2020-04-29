<template>
	<div id="header">
		<div class="nav-global">
			<div class="container">
				<h1 class="nav-logo">
					<a href="javascript:;"></a>
				</h1>
				<ul class="nav-aside">
					<li class="nav-user">
					  <router-link to="/account">个人中心</router-link>
						<!--active-->
						<div class="nav-user-wrapper">
							<div class="nav-user-list">
								<dl class="nav-user-avatar">
									<dd><span class="ng-scope"></span></dd>
									<dt class="ng-binding">+86 138****9453</dt>
								</dl>
								<ul>
									<li class="order"><router-link to="/account" exact>我的订单</router-link></li>
									<!--<li class="support"><a href="javascript:;">售后服务</a></li>
									<li class="coupon"><a href="javascript:;">我的优惠</a></li>
									<li class="information"><a href="javascript:;">账户资料</a></li>-->
									<li class="address"><router-link to="/address">收货地址</router-link></li>
								<!--	<li class="logout"><a href="javascript:;">退出</a></li>-->
								</ul>
							</div>
						</div>
					</li>
					<!--active-->
					<car-panel class="nav-cart"></car-panel>
				</ul>
				<ul class="nav-list">
					<li><a href="javascript:;">我的商城</a></li>
					<li><a href="javascript:;">VUE</a></li>
					<li><a href="javascript:;">WEAKPACK</a></li>
					<li><a href="javascript:;">VUE-CLI</a></li>
					<li><a href="javascript:;">VUE-ROUTER</a></li>
					<li><a href="javascript:;">VUEX</a></li>
					<li><a href="javascript:;">官方论坛</a></li>
				</ul>
			</div>
		</div>
		<div class="nav-sub">
			<div class="nav-sub-wrapper">
				<div class="container">
					<ul class="nav-list">
						<router-link to="/" exact tag="li" activeClass="active">
						    <a>首页</a>
						</router-link>
						<li><a href="javascript:;">手机</a></li>
						<!-- <li><a href="javascript:;">手感膜</a></li> -->
						<li><a href="javascript:;">配件</a></li>
						<li><a href="javascript:;">周边产品</a></li>
						<li><a href="javascript:;">第三方配件</a></li>
						<li><a href="javascript:;">全部商品</a></li>
						<li><a href="javascript:;">服务</a></li>
					</ul>
				</div>
			</div>
		</div>
	</div>
</template>
<script>
import CarPanel from '@/components/car-panel'
export default {
  components: {
    CarPanel
  }
}
</script>
