<style src="./home.css"></style>
<template>
	<div id="app">
		<div class="main">
			<div class="container">
				<div class="profile">
					<img src="/profile.jpg" alt="" />
				</div>
				<div class="title">
					<h1 class="title-name">Deven Rathod</h1>
					<p>
						Full Stack Developer <br />
						<span class="highlight-text">@DeveloperSpot</span>
					</p>
				</div>
				<div class="social-container">
					<button
						class="github"
						onClick="location.href='https://github.com/devenrathod2'"
					>
						I'm On GitHub
					</button>
					<button
						class="twitter"
						onClick="location.href='https://twitter.com/IamDevenR'"
					>
						I'm Also on Twitter
					</button>
					<button
						class="linkedin"
						onClick="location.href='https://linkedin.com/in/devenrathod'"
					>
						Let's Make Connection
					</button>
					<button
						class="instagram"
						onClick="location.href='https://instagram.com/the_exploitz'"
					>
						Follow Me On Instagram
					</button>

					<div class="footer-text">
						<p>
							Design with <span class="highlight-text-red">&#10084;</span> By
							<span class="highlight-text">Deven Rathod</span>
						</p>
					</div>
				</div>
			</div>
		</div>
	</div>
</template>

<script>
export default {
	name: "DevenRathod",
	props: {
		msg: String,
	},
};
</script>
