<template>
	<header>
		<!--<v-btn color="primary" fab bottom right large fixed @click="$vuetify.goTo(0)">
			<v-icon size="32">mdi-chevron-up</v-icon>
		</v-btn>-->
		<v-app-bar color="white" height="75" tag="div" app hide-on-scroll elevate-on-scroll>
			<v-container>
				<v-row no-gutters>
					<v-col cols="10" md="4">
						<v-toolbar-title>
							<app-logo />
						</v-toolbar-title>
					</v-col>
					<v-col cols="2" md="8">
						<div class="d-none d-md-flex justify-end">
							<div>
								<v-btn color="primary" text @click="$vuetify.goTo('#about')">About us</v-btn>
								<v-btn color="primary" text @click="$vuetify.goTo('#services')">Services</v-btn>
								<v-btn color="primary" text @click="$vuetify.goTo('#gallery')">Gallery</v-btn>
								<v-btn color="primary" text @click="$vuetify.goTo('#contact')">Contact</v-btn>
							</div>
						</div>
						<div class="d-md-none d-flex justify-end">
							<v-menu transition="scroll-y-transition" left offset-y>
								<template v-slot:activator="{ on, attrs }">
									<v-btn class="px-3" min-width="40" depressed v-bind="attrs" v-on="on">
										<v-icon>mdi-menu</v-icon>
									</v-btn>
								</template>
								<v-list min-width="200">
									<v-list-item @click="$vuetify.goTo('#about')">
										<v-list-item-title>About us</v-list-item-title>
									</v-list-item>
									<v-list-item @click="$vuetify.goTo('#services')">
										<v-list-item-title>Services</v-list-item-title>
									</v-list-item>
									<v-list-item @click="$vuetify.goTo('#gallery')">
										<v-list-item-title>Gallery</v-list-item-title>
									</v-list-item>
									<v-list-item @click="$vuetify.goTo('#contact')">
										<v-list-item-title>Contact</v-list-item-title>
									</v-list-item>
								</v-list>
							</v-menu>
						</div>
					</v-col>
				</v-row>
			</v-container>
		</v-app-bar>
	</header>
</template>
