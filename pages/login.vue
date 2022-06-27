<template>
	<div class="auth">
		<div class="auth-wrapper">
			<div class="auth-content">

			</div>
			<div class="auth-form">
				<login-form/>
			</div>
		</div>
	</div>
</template>

<script>
import LoginForm from "~/components/frontend/pages/login/loginForm";
export default {
	name: 'loginPage',
	components: {
		LoginForm
	},
	head: {
		title: 'Login'
	}
}
</script>
