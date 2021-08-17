<template>
	<div>
        <h1>Hello App!</h1>
        <p>
            <router-link to="/">Go to Home</router-link>
            <router-link to="/about">Go to About</router-link>
        </p>
        <!-- route outlet -->
        <!-- component matched by the route will render here -->
        <router-view></router-view>
	</div>
</template>

<script>
	
	export default {

	}

</script>

<style>

</style>