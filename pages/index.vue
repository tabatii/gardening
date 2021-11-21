<template>
	<div>
		<section class="pa-0">
			<v-parallax src="/wallpapers/2.jpg" height="700">
				<div class="wrapper">
					<v-container>
						<v-row justify="center" no-gutters>
							<v-col sm="9" lg="7">
								<div class="text-center">
									<div class="warning--text text-overline"><span>Welcome</span></div>
									<h3 class="white--text text-h3 text-sm-h2 font-weight-thin mb-8">Save Your Time by Using our Gardening Services</h3>
									<v-btn color="white" rounded outlined x-large @click="$vuetify.goTo(`#about`)">About us</v-btn>
								</div>
							</v-col>
						</v-row>
					</v-container>
				</div>
			</v-parallax>
		</section>
		<section>
			<v-container class="pa-0">
				<v-row justify="center" no-gutters>
					<v-col lg="9" xl="6">
						<v-card style="margin-top:-175px">
							<v-card-text class="body-1 text--primary pa-8">
								<v-row>
									<v-col class="order-2 order-sm-1" cols="12" sm="4">
										<div class="text-center">
											<div class="mb-2">
												<v-btn :href="whatsapp" target="_blank" color="primary" fab depressed large>
													<v-icon size="32" dark>mdi-phone</v-icon>
												</v-btn>
											</div>
											<p class="mb-0">+{{ $config.phone }}</p>
										</div>
									</v-col>
									<v-col class="order-1 order-sm-2" cols="12" sm="4">
										<div class="text-center">
											<div class="mb-2">
												<v-btn :href="$config.map" target="_blank" color="primary" fab depressed large>
													<v-icon size="32" dark>mdi-map-marker</v-icon>
												</v-btn>
											</div>
											<p class="mb-0">
												<span>Ctra. de Fuentenueva 129</span>,
												<span>Galapagar</span>,
												<span>Madrid</span>,
												<span>28260</span>
											</p>
										</div>
									</v-col>
									<v-col class="order-3" cols="12" sm="4">
										<div class="text-center">
											<div class="mb-2">
												<v-btn :href="`mailto:${$config.email}`" target="_blank" color="primary" fab depressed large>
													<v-icon size="32" dark>mdi-email-outline</v-icon>
												</v-btn>
											</div>
											<p class="mb-0">{{ $config.email }}</p>
										</div>
									</v-col>
								</v-row>
							</v-card-text>
						</v-card>
					</v-col>
				</v-row>
			</v-container>
		</section>
		<section>
			<div id="about">
				<v-container>
					<v-row justify="center" no-gutters>
						<v-col lg="9" xl="6">
							<h2 class="text-h4 text-sm-h3 text-center font-weight-light mb-8" data-aos="fade-up">
								WHO <span class="primary--text">WE ARE</span>
							</h2>
							<p class="text-h6 text-center font-weight-light" data-aos="fade-up" data-aos-duration="1000">
								The standard chunk of Lorem Ipsum used since the 1500s is reproduced below for those interested. Sections 1.10.32 and 1.10.33 from "de Finibus Bonorum et Malorum" by Cicero are also reproduced in their exact original form, accompanied by English versions from the 1914 translation by H. Rackham.
							</p>
						</v-col>
					</v-row>
				</v-container>
			</div>
		</section>
		<section class="bg">
			<div id="services">
				<v-container>
					<h2 class="text-h4 text-sm-h3 text-center font-weight-light mb-12" data-aos="fade-up">
						WHAT <span class="primary--text">WE DO</span>
					</h2>
					<v-row justify="center" data-aos="fade-up" data-aos-duration="1000">
						<v-col cols="12" sm="6" md="3" xl="2">
							<v-card class="item">
								<div class="text-center pa-4 pb-0">
									<v-avatar class="img" color="background" size="96">
										<v-img src="/png/green/6.png" />
									</v-avatar>
								</div>
								<v-card-title class="justify-center">Title here</v-card-title>
								<v-card-text class="text-center">Lorem ipsum dolor sit amet, consectetur adipiscing elit. Praesent ex.</v-card-text>
							</v-card>
						</v-col>
						<v-col cols="12" sm="6" md="3" xl="2">
							<v-card class="item">
								<div class="text-center pa-4 pb-0">
									<v-avatar class="img" color="background" size="96">
										<v-img src="/png/green/7.png" />
									</v-avatar>
								</div>
								<v-card-title class="justify-center">Title here</v-card-title>
								<v-card-text class="text-center">Lorem ipsum dolor sit amet, consectetur adipiscing elit. Praesent ex.</v-card-text>
							</v-card>
						</v-col>
						<v-col cols="12" sm="6" md="3" xl="2">
							<v-card class="item">
								<div class="text-center pa-4 pb-0">
									<v-avatar class="img" color="background" size="96">
										<v-img src="/png/green/5.png" />
									</v-avatar>
								</div>
								<v-card-title class="justify-center">Title here</v-card-title>
								<v-card-text class="text-center">Lorem ipsum dolor sit amet, consectetur adipiscing elit. Praesent ex.</v-card-text>
							</v-card>
						</v-col>
						<v-col cols="12" sm="6" md="3" xl="2">
							<v-card class="item">
								<div class="text-center pa-4 pb-0">
									<v-avatar class="img" color="background" size="96">
										<v-img src="/png/green/3.png" />
									</v-avatar>
								</div>
								<v-card-title class="justify-center">Title here</v-card-title>
								<v-card-text class="text-center">Lorem ipsum dolor sit amet, consectetur adipiscing elit. Praesent ex.</v-card-text>
							</v-card>
						</v-col>
					</v-row>
				</v-container>
			</div>
		</section>
		<section>
			<div id="gallery">
				<v-container class="px-0" fluid>
					<h2 class="text-h4 text-sm-h3 text-center font-weight-light mb-12" data-aos="fade-up">
						OUR <span class="primary--text">WORK</span>
					</h2>
					<v-row no-gutters data-aos="fade-up" data-aos-duration="1000">
						<v-col class="item" cols="12" sm="6" md="3">
							<v-img class="img" src="/gallery/1.jpg" />
							<div class="text">
								<p class="text-center text-h6 mb-2">Title Here</p>
								<p class="text-center subtitle-2 mb-0">Feb 5, 2018</p>
							</div>
						</v-col>
						<v-col class="item" cols="12" sm="6" md="3">
							<v-img class="img" src="/gallery/3.jpg" />
							<div class="text">
								<p class="text-center text-h6 mb-2">Title Here</p>
								<p class="text-center subtitle-2 mb-0">Feb 5, 2018</p>
							</div>
						</v-col>
						<v-col class="item" cols="12" sm="6" md="3">
							<v-img class="img" src="/gallery/4.jpg" />
							<div class="text">
								<p class="text-center text-h6 mb-2">Title Here</p>
								<p class="text-center subtitle-2 mb-0">Feb 5, 2018</p>
							</div>
						</v-col>
						<v-col class="item" cols="12" sm="6" md="3">
							<v-img class="img" src="/gallery/2.jpg" />
							<div class="text">
								<p class="text-center text-h6 mb-2">Title Here</p>
								<p class="text-center subtitle-2 mb-0">Feb 5, 2018</p>
							</div>
						</v-col>
					</v-row>
				</v-container>
			</div>
		</section>
		<div class="line mx-auto" style="width:60px"></div>
		<section>
			<div id="contact">
				<v-container>
					<h2 class="text-h4 text-sm-h3 text-center font-weight-light mb-12" data-aos="fade-up">
						GET <span class="primary--text">IN TOUCH</span>
					</h2>
					<v-row justify="center" data-aos="fade-up" data-aos-duration="1000">
						<v-col cols="12" xl="8">
							<v-text-field label="NAME" outlined hide-details />
						</v-col>
						<v-col cols="12" xl="8">
							<v-row>
								<v-col cols="12" sm="6">
									<v-text-field label="EMAIL" outlined hide-details />
								</v-col>
								<v-col cols="12" sm="6">
									<v-text-field label="MOBILE" outlined hide-details />
								</v-col>
							</v-row>
						</v-col>
						<v-col cols="12" xl="8">
							<v-textarea label="MESSAGE" outlined auto-grow no-resize hide-details />
						</v-col>
						<v-col cols="12" xl="8">
							<v-btn color="primary" block x-large>SEND</v-btn>
						</v-col>
					</v-row>
				</v-container>
			</div>
		</section>
		<section></section>
	</div>
</template>

<script>
	export default {
		computed: {
			whatsapp () {
				return `https://api.whatsapp.com/send?phone=${this.$config.phone}`
			}
		}
	}
</script>

<style scoped>
	.wrapper {
		position: absolute;
		top: 0;
		left: 0;
		right: 0;
		bottom: 0;
		display: flex;
		align-items: center;
		padding-bottom: 50px;
		background-image: linear-gradient(to right, rgba(76,175,80,.46), rgba(33,33,33,.46), rgba(76,175,80,.46));
	}
	.wrapper:after {
		content: "";
		position: absolute;
		bottom: 0;
		left: 0;
		right: 0;
		height: 40px;
		background-image: url('@/static/png/white/1.png');
		background-position: bottom center;
		background-repeat: repeat-x;
		background-size: 149px 30px;
	}
	#services .item {
		transition: .15s ease-in-out;
	}
	#services .img {
		transition: .5s ease-in-out;
	}
	#services .item:hover {
		transform: scale(1.1, 1.1);
	}
	#services .item:hover .img {
		transform: rotate(360deg);
	}
	#gallery .item {
		position: relative;
		overflow: hidden;
	}
	#gallery .img {
		transition: .25s ease-in-out;
	}
	#gallery .text {
		position: absolute;
		left: 0;
		right: 0;
		bottom: -94px;
		padding: 1rem;
		color: white;
		background-color: var(--v-primary-base);
		transition: .25s ease-in-out;
	}
	#gallery .item:hover .img {
		transform: translateY(-47px);
	}
	#gallery .item:hover .text {
		bottom: 0;
	}
</style>
