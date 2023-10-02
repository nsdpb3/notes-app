<template>
	<div class="wrapper">
		<div class="wrapper-content">
			<section>
				<div class="container">
					<h1>{{ title }}</h1>
					<message />
				</div>
			</section>
		</div>
	</div>
</template>

<script>
import Message from "@/components/Message.vue";
export default {
	components: {
		Message,
	},
	data() {
		return {
			title: "Notes App",
		};
	},
};
</script>

<style></style>
