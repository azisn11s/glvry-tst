<template>
	<div class="bg-white sticky-top">
		<b-navbar toggleable="lg" class=" container bg-white">
			<b-navbar-brand href="#" style="max-width: 150px">
				<b-img src="~/static/logo-grabfood.png" fluid alt="GrabFood" />
			</b-navbar-brand>

			<b-navbar-toggle target="nav-collapse"></b-navbar-toggle>

			<b-collapse id="nav-collapse" is-nav>
				<b-navbar-nav>
					<b-nav-form>
						<b-form-input
							size="lg"
							class="ml-lg-3"
							placeholder="Type your location..."
						></b-form-input>
					</b-nav-form>
				</b-navbar-nav>

				<!-- Right aligned nav items -->
				<b-navbar-nav class="ml-auto">
					<b-button
						class="my-2 my-sm-0 btn-outline-dark"
						variant="outline-dark"
					>
						<b-icon icon="basket2" />
					</b-button>

					<b-button
						class="my-2 my-sm-0 ml-lg-2 btn-outline-dark"
						variant="outline-dark"
						>Login/Signup</b-button
					>
				</b-navbar-nav>
			</b-collapse>
		</b-navbar>
	</div>
</template>

<script>
export default {};
</script>

<style>
</style>