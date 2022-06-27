<template>
	<div class="auth">
		<div class="auth-wrapper">
			<div class="auth-content">

			</div>
			<div class="auth-form">
				<register-form/>
			</div>
		</div>
	</div>
</template>

<script>
import RegisterForm from "~/components/frontend/pages/register/registerForm";
export default {
	name: 'registerPage',
	components: {
		RegisterForm
	},
	head: {
		title: 'Register'
	}
}
</script>
