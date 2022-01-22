<template>
	<div class="mt-4">
		<Header />

		<!-- <main role="main"> -->
		<MyJumbotron />
		<!-- <MyCarousel /> -->

		<MyMenu />
		<!-- </main> -->

		<section class="bg-light">
			<b-container class="products-container">
        <h3 class="category-title">Aigo</h3>
				<b-row>
					
          <MyProduct />
          <MyProduct />
          <MyProduct />

          
				</b-row>
			</b-container>
		</section>
	</div>
</template>

<script>
export default {
	name: "IndexPage",
};
</script>

<style lang="css" scoped>
.sticky-header {
	top: 68px;
}
.products-container {
	display: block;
	padding-top: 5%;
	padding-bottom: 5%;
}
.category-title {
  font-weight: bold;
  margin-bottom: 3%;
}
</style>
