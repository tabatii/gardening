<template>
	<v-footer color="white" padless>
		<v-container class="pa-0" fluid>
			<v-divider></v-divider>
		</v-container>
		<v-container class="py-8">
			<v-row justify="center" align="center">
				<v-col cols="4">
					<div class="font-weight-light">
						<span>© 2021 COMPANY NAME</span>
						<span class="mx-3">|</span>
						<span>Designed by Tabatii</span>
					</div>
				</v-col>
				<v-col cols="4">
					<div class="d-flex justify-end">
						<v-btn icon><v-icon>mdi-facebook</v-icon></v-btn>
						<v-btn icon><v-icon>mdi-instagram</v-icon></v-btn>
						<v-btn icon><v-icon>mdi-linkedin</v-icon></v-btn>
					</div>
				</v-col>
			</v-row>
		</v-container>
	</v-footer>
</template>

<style scoped>
	.copyright {
		position: relative;
		padding: 2rem 0;
		text-align: center;
		font-weight: 100;
	}
	.copyright:before {
		content: "";
		position: absolute;
		top: -40px;
		left: 0;
		right: 0;
		height: 40px;
		background-image: url('@/static/png/green/2.png');
		background-position: bottom center;
		background-repeat: repeat-x;
		background-size: 149px 30px;
	}
</style>
