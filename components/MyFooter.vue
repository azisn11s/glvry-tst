<template>
	<footer class="footer-container">
		<section class="container">
			<b-row class="d-flex justify-content-between pt-4">
				<b-col lg="3">
					<b-img
						src="~/static/logo-grabfood-mono.svg"
						fluid
						alt="GrabFood"
					/>
				</b-col>

				<b-col lg="3" class="d-flex justify-content-end">
					<select class="form-control" style="max-width: 30%">
						<option>EN</option>
						<option>ID</option>
					</select>
				</b-col>
			</b-row>
			<hr class="solid-divider" />
		</section>

		<!-- Footer Menu -->
		<section class="container" style="margin-top: 3%">
			<b-row>
				<b-col>
					<h5 class="footer-menu-title mb-4">Frequently Searched</h5>
					<ul class="redirect-list">
						<li>
							<a href="#">Burger King Menu</a>
						</li>
						<li>
							<a href="#">Chatime Menu</a>
						</li>
						<li>
							<a href="#">Domino's Pizza Menu</a>
						</li>
						<li>
							<a href="#">Hokben Menu</a>
						</li>
						<li>
							<a href="#">JCO Delivery</a>
						</li>
						<li>
							<a href="#">KFC Menu</a>
						</li>
						<li>
							<a href="#">McDonalds Menu</a>
						</li>
						<li>
							<a href="#">Pizza Hut Delivery</a>
						</li>
						<li>
							<a href="#">Richeese Menu</a>
						</li>
						<li>
							<a href="#">Menu Solaria</a>
						</li>
						<li>
							<a href="#">Starbucks Menu</a>
						</li>
						<li>
							<a href="#">Yoshinoya Menu</a>
						</li>
					</ul>
				</b-col>
				<b-col>
					<h5 class="footer-menu-title mb-4">Popular Cuisines</h5>
					<ul class="redirect-list">
						<li>
							<a href="#">Chinese Food</a>
						</li>
						<li>
							<a href="#">Fast Food</a>
						</li>
						<li>
							<a href="#">Indian Food</a>
						</li>
						<li>
							<a href="#">Indonesian Food</a>
						</li>
						<li>
							<a href="#">Italian Food</a>
						</li>
						<li>
							<a href="#">Japanese Food</a>
						</li>
						<li>
							<a href="#">Korean Food</a>
						</li>
						<li>
							<a href="#">Thai Food</a>
						</li>
						<li>
							<a href="#">Vietnamese Food</a>
						</li>
					</ul>
				</b-col>
				<b-col>
					<h5 class="footer-menu-title mb-4">About Grab</h5>
					<ul class="redirect-list">
						<li>
							<a href="#">About Grab</a>
						</li>
						<li>
							<a href="#">About GrabFood</a>
						</li>
						<li>
							<a href="#">Blog</a>
						</li>
					</ul>
				</b-col>
				<b-col>
					<h5 class="footer-menu-title mb-4">Support</h5>
					<ul class="redirect-list">
						<li>
							<a href="#">Help</a>
						</li>
						<li>
							<a href="#">FAQs</a>
						</li>
						<li>
							<a href="#">Be a GrabFood Merchant</a>
						</li>
						<li>
							<a href="#">Drive With Grab</a>
						</li>
					</ul>
				</b-col>
			</b-row>
		</section>

		<!-- Footer bottom -->
		<section class="footer-bottom">
			<div class="container">
				<b-row>
					<b-col>
						<h5>Countries with GrabFood</h5>
                        <div class="countries">
                            <ul>
                                <li><a href="#">Indonesia</a></li>
                                <li><a href="#">Philippines</a></li>
                                <li><a href="#">Thailand</a></li>
                                <li><a href="#">Vietnam</a></li>
                                <li><a href="#">Singapore</a></li>
                                <li><a href="#">Malaysia</a></li>
                                <li><a href="#">Myanmar</a></li>
                            </ul>
                        </div>
					</b-col>
				</b-row>
			</div>

            <div class="container">
                <b-row>
                    <b-col>
                        <span>© Grab 2022</span>
                    </b-col>
                </b-row>
                <b-row>
                    <b-col></b-col>
                </b-row>
            </div>
		</section>
	</footer>
</template>

<script>
export default {};
</script>

<style scoped>
.footer-container {
	background-color: #eaeff2;
}
.solid-divider {
	border-top: 1px solid rgb(184, 181, 181);
}
.footer-menu-title {
	font-weight: bold;
	font-size: 17px;
	color: rgb(97, 95, 95);
}
ul.redirect-list,
ul.redirect-list li,
ul.redirect-list ul li {
	margin: 0;
	padding: 0;
	text-indent: 0;
	list-style: none;
}
ul.redirect-list > li > a {
	color: rgb(85, 81, 81);
}
.footer-bottom {
	margin-top: 5%;
	background-color: #363a45;
    padding-bottom: 3%;
}
.footer-bottom .container {
	color: blanchedalmond;
    padding-top: 2%
}
.footer-bottom ul {
	list-style-type: none;
  margin: 0;
  padding: 0;
}
.footer-bottom li{
    float: left;
}
.footer-bottom li a {
  display: block;
  color: white;
  text-align: center;
  padding-right: 14px;
  text-decoration: none;
}
</style>