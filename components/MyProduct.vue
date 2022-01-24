<template>
	<b-col>
		<b-card no-body class="overflow-hidden" style="max-width: 400px; max-height: 200px">
			<b-row no-gutters>
				<b-col md="4" class="pl-3 pt-3">
					<b-card-img
						src="https://picsum.photos/400/400/?image=20"
						alt="Image"
						class="rounded-2"
					></b-card-img>
				</b-col>
				<b-col md="8">
					<b-card-body title="Horizontal Card" class="pt-3">
						<b-card-text class="text-muted">
							Nasi Putih + Udang goreng saos telur asin
						</b-card-text>
					</b-card-body>
                    <b-card-footer class="d-flex justify-content-end bg-white border-white">
                        <b-button size="sm" variant="success">
                            <b-icon icon="plus" font-scale="1.5" />
                        </b-button>
                    </b-card-footer>
				</b-col>
			</b-row>
		</b-card>
	</b-col>
</template>

<script>
export default {};
</script>

<style scoped>

</style>