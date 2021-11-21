<template>
	<v-footer color="background" padless>
		<v-container class="pa-0" fluid>
			<v-divider></v-divider>
		</v-container>
		<v-container class="py-8">
			<v-row justify="center" align="center">
				<v-col class="order-last order-sm-first" cols="12" sm="9" xl="6">
					<div class="text-center text-sm-left">
						<span class="d-block d-sm-inline">© 2021 {{ $config.name }}</span>
						<span class="d-none d-sm-inline mx-3">|</span>
						<span class="d-block d-sm-inline">Designed by {{ $config.dev }}</span>
					</div>
				</v-col>
				<v-col class="order-first order-sm-last" cols="12" sm="3" xl="2">
					<div class="d-flex justify-center justify-sm-end">
						<v-btn icon><v-icon class="text--primary">mdi-facebook</v-icon></v-btn>
						<v-btn icon><v-icon class="text--primary">mdi-instagram</v-icon></v-btn>
						<v-btn icon><v-icon class="text--primary">mdi-linkedin</v-icon></v-btn>
					</div>
				</v-col>
			</v-row>
		</v-container>
	</v-footer>
</template>
