// ./components/homeLink.vue
<template>
    <div id="app">
		<nav>
			<NavLink url="/" text="Accueil" />
			<NavLink url="/about" text="À propos" />
			<NavLink url="/contact" text="Contact" />
		</nav>
	</div>
</template>

<script>
import navLink from './components/navLink.vue'

export default {
    name: 'HomeLink',
    components: {
        navLink
    }
}
</script>

<style>
    a {
        font-weight: 800;
    }

</style>