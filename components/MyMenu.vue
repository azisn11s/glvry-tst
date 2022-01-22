<template>
	<section class="w-100 d-flex align-items-end border-bottom sticky-top sticky-header bg-white" style="height: 75px">
		<div class="container">
            <ul class="d-flex food-categories">
                <li class="pr-3">
                    <b-link href="#">Aigo</b-link>
                </li>
                <li class="pr-3">
                    <b-link href="#">Chingu</b-link>
                </li>
                <li class="pr-3">
                    <b-link href="#">Seerameon Ikan</b-link>
                </li>
                <li class="pr-3">
                    <b-link href="#">Samjang Gami</b-link>
                </li>
                <li class="pr-3">
                    <b-link href="#">Sea Monster</b-link>
                </li>
                <li class="pr-3">
                    <b-link href="#">Omo</b-link>
                </li>
                <li class="pr-3">
                    <b-link href="#">Saranghaeyo</b-link>
                </li>
                <li class="pr-3">
                    <b-link href="#">Chaeso</b-link>
                </li>
                <li class="pr-3">
                    <b-link href="#">Drink (Ice/Hot)</b-link>
                </li>
                <li class="pr-3">
                    <b-link href="#">Addon</b-link>
                </li>
            </ul>
        </div>
	</section>
</template>

<script>
export default {};
</script>

<style scoped>
.sticky-header{
    -moz-box-shadow: 0 4px 2px rgba(139, 137, 137, 0.158);
    -webkit-box-shadow: 0 4px 2px rgba(139, 137, 137, 0.158);
    box-shadow: 0 4px 2px rgba(139, 137, 137, 0.158);
}
.food-categories {
    margin: 0;
    padding: 0;
    overflow-x: hidden;
}
.food-categories > li {
    list-style-type: none;
}
.food-categories li a {
    display: block;
    padding-bottom: 13px;
    font-size: 16px;;
    width: 120px;
    text-align: center;
    color: grey;
    /* padding-right: 100px; */

}

</style>