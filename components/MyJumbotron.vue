<template>
	<div class="container">
        <div class="w-100 my-jumbotron">
		<b-row class="">
			<b-col>
				<b-breadcrumb class="bg-white pl-0">
					<b-breadcrumb-item href="#home">Home</b-breadcrumb-item>
					<b-breadcrumb-item href="#foo">Restaurant</b-breadcrumb-item>
					<b-breadcrumb-item href="#bar" active>Do Yan Seafood - Sumbersekar</b-breadcrumb-item>
				</b-breadcrumb>
			</b-col>
		</b-row>
        <b-row>
            <b-col>
                <span class="label-prefered-merchant text-success font-weight-bold">
                    <b-icon icon="patch-check"></b-icon>
                    Prefered Merchant
                </span>
            </b-col>
        </b-row>
        <b-row class="mt-2">
            <b-col>
                <h1 class="font-weight-bold">
                    Do Yan Seafood - Sumbersekar
                </h1>
            </b-col>
        </b-row>
        <b-row class="mt-1">
            <b-col>
                <span class="categories text-muted">
                    Seafood,Snack
                </span>
            </b-col>
        </b-row>
        <b-row class="mt-1">
            <b-col>
                <span class="rating text-muted">
                    <b-icon icon="star-fill" variant="warning" />
                    4.7
                </span>
                <span class="distance text-muted ml-4">
                    664.1 km
                </span>
            </b-col>
        </b-row>
        <b-row class="mt-3">
            <b-col>
                <span class="font-weight-bold">
                    Opening Hours
                </span>
                <span class="ml-4 text-muted">
                    Today 13:00 - 22:00
                </span>
            </b-col>
        </b-row>
        <b-row class="mt-2">
            <b-col>
                <span class="">
                    <b-icon icon="tag" class="text-success" />
                    DUKUNGUMKM 60% | HEMAT40 40% | HEMAT35 35%
                </span>
                <a class="ml-2 font-size-bold link">
                    See details
                </a>
            </b-col>
        </b-row>
        <b-row>
            <b-col>
                <span class="">
                    <b-icon icon="info-circle" class="text-muted" />
                    Order fee of Rp3.000 applies for this restaurant.
                </span>
            </b-col>
        </b-row>

        <b-row class="mt-4">
            <b-col>
                <b-nav-form>
					<b-form-datepicker id="example-datepicker" v-model="deliver_date" class="form-control-lg" style="z-index: 9999;"></b-form-datepicker>
                    <b-form-timepicker v-model="deliver_time" locale="id" class="form-control-lg ml-lg-4" style="z-index: 9999;"></b-form-timepicker>
				</b-nav-form>
            </b-col>
        </b-row>
	</div>
    </div>
</template>

<script>
export default {
    data(){
        return {
            deliver_date: new Date(),
            deliver_time: ''
        }
    }
};
</script>

<style scoped>
.my-jumbotron {
	position: relative;
    top: 10vh;
    padding-bottom: 5%;
    margin-bottom: 6%;
}
</style>