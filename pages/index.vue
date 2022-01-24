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
				<h2 class="category-title">Aigo</h2>
				<b-row class="mb-4">
					<MyProduct />
					<MyProduct />
					<MyProduct />
				</b-row>
				<b-row class="mb-4">
					<MyProduct />
					<MyProduct />
					<MyProduct />
				</b-row>
			</b-container>

			<b-container class="products-container">
				<h2 class="category-title">Seerameon Ikan</h2>
				<b-row class="mb-4">
					<MyProduct />
					<MyProduct />
					<MyProduct />
				</b-row>
				<b-row class="mb-4">
					<MyProduct />
					<MyProduct />
					<MyProduct />
				</b-row>
			</b-container>

			<b-container class="products-container">
				<h2 class="category-title">Samjang Gami ( Extra Pedas )</h2>
				<b-row class="mb-4">
					<MyProduct />
					<MyProduct />
					<MyProduct />
				</b-row>
				<b-row class="mb-4">
					<MyProduct />
					<MyProduct />
					<MyProduct />
				</b-row>
			</b-container>


		</section>

		<MyFooter />

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
	padding-top: 2%;
	padding-bottom: 2%;
}
.category-title {
	font-weight: bold;
	margin-bottom: 3%;
}
</style>
