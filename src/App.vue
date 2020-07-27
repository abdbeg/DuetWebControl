<style>
#title:not(:hover) {
	color: inherit;
}
#title {
	margin-right: 20px;
}

.empty-table-fix td {
	padding-left: 0px !important;
	padding-right: 0px !important;
}

.global-control.theme--light {
	background-color: #F5F5F5 !important;
}
#global-container .v-card.theme--light {
	background-color: #F5F5F5 !important;
}
.global-control {
	background-color: #515151 !important;
}
#global-container .v-card {
	background-color: #515151 !important;
}

input[type='number'] {
    -moz-appearance: textfield;
}

input::-webkit-outer-spin-button,
input::-webkit-inner-spin-button {
    -webkit-appearance: none;
}

a:not(:hover) {
	text-decoration: none;
}

textarea {
	line-height: 1.25rem !important;
}

 textarea {
	caret-color: #FFF;
}

.v-item-group .v-btn__content {
	color: #FFF !important;
}

.v-card__title {
	font-size: 1rem;
}
.v-application--is-ltr .v-chip .v-chip__close.v-icon.v-icon--right {
    margin-right: 0 !important;
    margin-bottom: 0;
}

/* Custom CSS */



/* Dark theme scrollbar */
/* Track */
.theme--dark ::-webkit-scrollbar-track, body::-webkit-scrollbar-track {
  background: #272727;
}

/* Handle */
.theme--dark ::-webkit-scrollbar-thumb, ::-webkit-scrollbar-thumb {
  background: #3c3c3c;
  border-radius: 10px;
  border: 4px solid;
  border-color: #272727;
}

/* Handle on hover */
.theme--dark ::-webkit-scrollbar-thumb:hover, ::-webkit-scrollbar-thumb:hover {
  background: #808080;
  display:block;
  border: 1px solid #808080;
}

/* width */
.theme--dark ::-webkit-scrollbar, ::-webkit-scrollbar {
  width: 15px;
  border-radius: 10px;

}

/* Handle light */
.theme--light ::-webkit-scrollbar-thumb {
  border-color: #FFFFFF;
}

.v-chip:not(.v-chip--active) {
    margin: 3px;
}
#global-container .v-card {
    height: 100%;
}

#global-container .v-card {
    height: 100%;
    display: table;
    width: 100%;
}

 .v-card__text.px-0.pt-0.pb-2.content.text-xs-center {
    vertical-align: middle;
    display: table-row;
}

.v-card__title.py-2 {
    vertical-align: top;
}

 .v-card__title.py-2 {
    text-align: center;
}
 .v-card .v-icon {
    margin-right: 5px !important;
    margin-bottom: 3px;
}
 .v-card:not(.v-sheet--tile):not(.v-card--shaped) {
    border-radius: 10px !important;
}
 .v-alert:not(.v-sheet--tile) {
    border-radius: 5px;
}
.v-navigation-drawer:not(.v-navigation-drawer--floating) .v-navigation-drawer__border {
    display: none;
}
hr.v-divider {
    display: none;
}
hr.my-2.v-divider {
    display: block;
}
tr .v-divider {
    display: block;
}
 .row.flex-nowrap.no-gutters {
    margin-bottom: 4%;
    margin-top: 3%;
}
 .v-alert:not(.v-sheet--tile) {
    border-radius: 10px;
}
 .no-gutters > .col:first-child button {
    border-top-left-radius: 5px;
    border-bottom-left-radius: 5px;
}

 .no-gutters > .col:last-child button {
    border-top-right-radius: 5px;
    border-bottom-right-radius: 5px;
}
.v-app-bar__nav-icon {
    display: none;
}
@media only screen and (max-width: 800px) {

	.v-app-bar__nav-icon {
		display: block !important;
	}

	.v-list-group__header__append-icon {
		display: block !important;
	}
}
.v-list-group__header__append-icon {
    display: none;
}
.theme--dark.v-application {
    background: #363636;
    color: #FFFFFF;
}
.v-list-item--link:before {
    border-top-right-radius: 10px;
	border-bottom-right-radius: 10px;
    margin-right: 10px;
    margin-top: 1px;
    margin-bottom: 1px;
}
.v-card {
    box-shadow: 0 3px 5px -1px rgba(0,0,0,.2),0 6px 10px 0 rgba(0,0,0,.14),0 1px 18px 0 rgba(0,0,0,.12)!important;
}
.v-navigation-drawer--clipped:not(.v-navigation-drawer--temporary):not(.v-navigation-drawer--is-mobile) {
    box-shadow: 0 3px 5px -1px rgba(0,0,0,.2),0 6px 10px 0 rgba(0,0,0,.14),0 1px 18px 0 rgba(0,0,0,.12)!important;
}
.v-navigation-drawer--clipped:not(.v-navigation-drawer--temporary):not(.v-navigation-drawer--is-mobile) {
    width: 289px !important;
}
main#content {
    padding-top: 77px !important;
}
.v-card__title {
    font-size: 18px;
}
.pt-1 .v-btn.v-btn--contained.v-size--default {
    padding: 24px;
}
.v-card__text.pt-0 .v-btn.v-btn--block.v-btn--contained.theme--dark.v-size--default:first-child {
    margin-bottom: 10px;
}
.layout.pt-2.px-2.justify-center.column {
    padding: 25px !important;
}
.v-menu__content.theme--dark.menuable__content__active {
    left: 1082px !important;
}
html .v-card__title.py-2 {
    padding: 25px !important;
}
.v-card__title.pt-2.pb-0 {
    padding: 25px !important;
}
.v-card__title {
    padding: 25px !important;
}
.v-application a {
    -webkit-animation: fadein 2s;
    transition: 0.3s;
}
.v-application a:hover {
	color: #144371;
    text-decoration: none;
	transition: 0.3s;
}
header.v-sheet.v-sheet--tile.v-toolbar {
    border-radius: 10px;
}
.v-data-table.base-file-list.elevation-3 {
    border-radius: 10px;
}
.mb-2.v-card.v-sheet .v-card__title {
    padding-left: 16px !important;
    padding-right: 16px !important;
}
.v-data-table.elevation-3 {
    border-radius: 10px;
}
.v-menu__content {
    transition: 0.1s;
}
.row.flex-nowrap.no-gutters:first-child {
    margin-top: -3%;
}
.v-btn-toggle:not(.v-btn-toggle--group) .v-btn.v-btn {
    border: none;
}

.flex-shrink-1.col.col-auto .v-btn.v-btn--block.v-btn--contained.v-btn--tile.v-size--default {
    border-radius: 5px;
}

.flex-shrink-1.col.col-auto .v-btn.v-btn--block.v-btn--contained.v-btn--tile.v-size--default:first-child {
    margin-top: -5%;
    margin-bottom: 5%;
}

.tool-input[data-v-34b8025c] {
    max-width: 88%;
}
table.tools th[data-v-ba90406e]:nth-child(2) {
    width: 16%;
}
table.tools th[data-v-ba90406e]:nth-child(4) {
    width: 23%;
}
table.tools th[data-v-ba90406e]:nth-child(5) {
    width: 23%;
}
table.tools th[data-v-ba90406e]:nth-child(1) {
    width: 18%;
}
.row.mt-1.no-gutters .col {
    margin-top: 3%;
}
.v-card__title.pb-1 {
    padding-bottom: 25px !important;
}
.v-card__title.pb-0 {
    padding: 25px !important;
}
.v-card__text.text-center.pb-1 {
    padding-bottom: 16px !important;
}
.v-input.slider.v-input--hide-details.v-input--is-label-active.v-input--is-dirty.v-input__slider {
    margin-top: 0px;
}

.v-tabs .v-tab--active:hover::before, .v-tabs .v-tab--active::before {
    border-top-right-radius: 10px;
    border-top-left-radius: 10px;
}
.theme--light.v-tabs .v-tab:hover::before {
    border-radius: 10px;
    margin-left: 1%;
}
.v-ripple__container {
    border-radius: 10px;
    margin-left: 1%;
}
.mt-1.text-center {
    padding: 0 16px 16px 16px;
}
canvas.chartjs-render-monitor {
    position: relative;
}

.v-card__text.content.flex-grow-1.px-2.py-0 {
    padding: 0 16px 16px 16px !important;
}
.v-application .px-3 {
    padding-left: 16px !important;
    padding-right: 16px !important;
}
@media only screen and (max-width: 766px) {
	.mb-2.v-card.v-sheet .v-card__title .mx-0.v-btn.v-btn--contained.v-size--small {
		margin-top: 5%;
	}
	table.tools {
		width: max-content;
	}
	.v-card__text.pa-0 {
		overflow-x: auto;
	}
	.theme--dark .v-card__text.pa-0::-webkit-scrollbar-track {
	border-bottom-right-radius: 10px;
	border-bottom-left-radius: 10px;
	border-radius: 10px;
	}
	.theme--dark .v-card__text.pa-0::-webkit-scrollbar-thumb {
	border: 4px solid;
	border-color: #515151;
	}
	.theme--dark .v-card__text.pa-0::-webkit-scrollbar-track {
	background-color: #515151;
	}
	.theme--dark .v-card__text.pa-0::-webkit-scrollbar-thumb:active {
	border: 1px solid;
	border-color: #515151;
	}
	.theme--light .v-card__text.pa-0::-webkit-scrollbar-thumb {
	border: 4px solid;
	border-color: #F5F5F5;
	}
	.theme--light .v-card__text.pa-0::-webkit-scrollbar-thumb:active {
	border: 1px solid !important;
	border-color: #F5F5F5 !important;
	}
	.scroll-y-transition-leave-to {
    transition: 0.2s;
    transform: translateY(-50%) !important;
    opacity: 0;
	}
	th.text-start.sortable {
    width: 25% !important;
    padding-right: 0px;
	}
	span.v-icon.notranslate.v-data-table-header__icon.v-icon--svg.theme--light {
    margin-left: 6%;
    margin-top: -2%;
	}
	.console-list-custom .v-list-item:before {
    margin-right: 0;
    border-radius: 10px;
    margin-top: 0 !important;
	}
	.console-list-custom {
    padding: 0;
    border-radius: 10px !important;
	}
	.v-menu__content.menuable__content__active {
    border-radius: 10px;
	}
	.console-list-custom .v-ripple__container {
    margin-left: 0%;
	}
	h1[data-v-32b0d00f] {
    padding: 2%;
    line-height: 120%;
}
}

</style>

<script src="https://cdn.jsdelivr.net/npm/chart.js@2.9.3"></script>
<script src="https://cdn.jsdelivr.net/npm/hammerjs@2.0.8"></script>
<script src="https://cdn.jsdelivr.net/npm/chartjs-plugin-zoom@0.7.7"></script>

<template>
	<v-app>
		<v-navigation-drawer v-model="drawer" clipped fixed app width="300">
			<div class="pa-2 hidden-sm-and-up">
				<connect-btn v-if="isLocal" class="mb-3" block></connect-btn>
				<emergency-btn block></emergency-btn>
			</div>

			<v-list class="pt-0" :expand="$vuetify.breakpoint.mdAndUp">
				<v-list-group v-for="(category, index) in routing" :key="index" :prepend-icon="category.icon" no-action :value="isExpanded(category)">
					<template #activator>
						<v-list-item-title>{{ $t(category.caption) }}</v-list-item-title>
					</template>

					<v-list-item v-for="(page, pageIndex) in category.pages.filter(page => checkMenuCondition(page.condition))" :key="`${index}-${pageIndex}`" v-ripple :to="page.path" @click.prevent="">
						<v-list-item-icon>
							<v-icon>{{ page.icon }}</v-icon>
						</v-list-item-icon>
						<v-list-item-title>{{ $t(page.caption) }}</v-list-item-title>
					</v-list-item>
				</v-list-group>
			</v-list>
		</v-navigation-drawer>

		<v-app-bar ref="appToolbar" app clipped-left>
			<v-app-bar-nav-icon @click.stop="drawer = !drawer">
				<v-icon>mdi-menu</v-icon>
			</v-app-bar-nav-icon>
			<v-toolbar-title>
				<!-- TODO: Optional OEM branding -->
				<a href="javascript:void(0)" id="title">{{ name }}</a>
			</v-toolbar-title>
			<connect-btn v-if="isLocal" class="hidden-xs-only"></connect-btn>

			<v-spacer></v-spacer>

			<code-input class="mx-3 hidden-sm-and-down"></code-input>

			<v-spacer></v-spacer>

			<upload-btn target="start" class="mr-3 hidden-sm-and-down"></upload-btn>
			<emergency-btn class="hidden-xs-only"></emergency-btn>

			<v-btn icon class="hidden-md-and-up ml-3" :class="toggleGlobalContainerColor" @click="hideGlobalContainer = !hideGlobalContainer">
				<v-icon>mdi-aspect-ratio</v-icon>
			</v-btn>
		</v-app-bar>

		<v-content id="content">
			<v-scroll-y-transition>
				<v-container v-show="!hideGlobalContainer || $vuetify.breakpoint.mdAndUp" id="global-container" fluid class="py-0">
					<v-row>
						<v-col cols="12" sm="6" md="4" lg="4" xl="4">
							<status-panel></status-panel>
						</v-col>

						<v-col cols="12" sm="6" md="5" lg="5" xl="4">
							<tools-panel></tools-panel>
						</v-col>

						<v-col v-if="$vuetify.breakpoint.mdAndUp" :class="{ 'd-flex': hasTemperaturesToDisplay }" md="3" lg="3" xl="4">
							<temperature-chart></temperature-chart>
						</v-col>
					</v-row>
				</v-container>
			</v-scroll-y-transition>

			<v-divider v-show="!hideGlobalContainer || $vuetify.breakpoint.mdAndUp"></v-divider>

			<v-container fluid class="pt-0">
				<keep-alive>
					<router-view></router-view>
				</keep-alive>
			</v-container>
		</v-content>

		<connect-dialog></connect-dialog>
		<connection-dialog></connection-dialog>
		<messagebox-dialog></messagebox-dialog>
	</v-app>
</template>

<script>
'use strict'

import Piecon from 'piecon'
import { mapState, mapGetters, mapActions } from 'vuex'

import { Routing } from './routes'
import { isPrinting } from './store/machine/modelEnums.js'

export default {
	computed: {
		...mapState({
			isLocal: state => state.isLocal,
			globalShowConnectDialog: state => state.showConnectDialog,

			boards: state => state.machine.model.boards,
			menuDirectory: state => state.machine.model.directories.menu,
			name: state => state.machine.model.network.name,
			status: state => state.machine.model.state.status,

			darkTheme: state => state.settings.darkTheme,
			webcam: state => state.settings.webcam
		}),
		...mapGetters('machine', ['hasTemperaturesToDisplay']),
		...mapGetters('machine/model', ['jobProgress']),
		toggleGlobalContainerColor() {
			if (this.hideGlobalContainer) {
				return this.darkTheme ? 'red darken-5' : 'red lighten-4';
			}
			return this.darkTheme ? 'green darken-5' : 'green lighten-4';
		}
	},
	data() {
		return {
			drawer: this.$vuetify.breakpoint.lgAndUp,
			hideGlobalContainer: false,
			routing: Routing,
			wasXs: this.$vuetify.breakpoint.xsOnly
		}
	},
	methods: {
		...mapActions(['connect', 'disconnectAll']),
		...mapActions('settings', ['load']),
		checkMenuCondition(condition) {
			if (condition === 'webcam') {
				return (this.webcam.url !== '');
			}
			if (condition === 'display') {
				return (this.boards.length > 0) && this.boards[0].supports12864;
			}
			return true;
		},
		isExpanded(category) {
			if (this.$vuetify.breakpoint.xsOnly) {
				const route = this.$route;
				return category.pages.some(page => page.path === route.path);
			}
			return true;
		},
		updateTitle() {
			const jobProgress = this.jobProgress;
			const title = ((jobProgress > 0 && isPrinting(this.status)) ? `(${(jobProgress * 100).toFixed(1)}%) ` : '') + this.name;
			if (document.title !== title) {
				document.title = title;
			}
		}
	},
	mounted() {
		// Attempt to disconnect from every machine when the page is being unloaded
		window.addEventListener('unload', this.disconnectAll);

		// Connect if running on a board
		if (!this.isLocal) {
			this.connect();
		}

		// Attempt to load the settings
		this.load();

		// Validate navigation
		const that = this;
		this.$router.beforeEach((to, from, next) => {
			if (Routing.some(group => group.pages.some(page => page.path === to.path && !that.checkMenuCondition(page.condition)))) {
				next('/');
			} else {
				next();
			}
		});

		const route = this.$route;
		if (Routing.some(group => group.pages.some(page => page.path === route.path && !this.checkMenuCondition(page.condition)))) {
			this.$router.push('/');
		}

		// Set up Piecon
		Piecon.setOptions({
			color: '#00f',			// Pie chart color
			background: '#bbb',		// Empty pie chart color
			shadow: '#fff',			// Outer ring color
			fallback: false			// Toggles displaying percentage in the title bar (possible values - true, false, 'force')
		});
	},
	watch: {
		darkTheme(to) {
			this.$vuetify.theme.dark = to;
		},
		status(to, from) {
			const printing = isPrinting(to);
			if (printing !== isPrinting(from)) {
				if (printing) {
					// Go to Job Status when a print starts
					if (this.$router.currentRoute.path !== '/Job/Status') {
						this.$router.push('/Job/Status');
					}
				} else {
					// Remove the Piecon again when the print has finished
					Piecon.reset();
				}
			}
		},
		name() { this.updateTitle(); },
		jobProgress(to) {
			if (isPrinting(this.status)) {
				Piecon.setProgress(to * 100);
			}
			this.updateTitle();
		}
	}
}
</script>
