---
title: TEST
permalink: /permalink/
description: ""
---
<style>
	/* Add some basic styles */
	body {
		font-family: Arial, sans-serif;
		margin: 0;
		display: flex;
		justify-content: center;
		align-items: center;
		height: 100vh;
		background-color: #f4f4f4;
	}

	.header {
		text-align: center;
	}

	/* Add blinking cursor style */
	.cursor {
		display: inline-block;
		vertical-align: middle;
		width: 10px;
		height: 20px;
		background-color: #000;
		animation: blink 0.8s infinite;
	}

	/* Add typing animation keyframes */
	@keyframes typing {
		from {
			width: 0;
		}
		to {
			width: 100%;
		}
	}

	@keyframes blink {
		0%, 100% {
			opacity: 1;
		}
		50% {
			opacity: 0;
		}
	}
	.typed-text::after {
		content: '|';
		display: inline-block;
		animation: typing 3s steps(10) infinite;
	}
</style>


	<div class="header">
		<h1>
			<span class="typed-text">ext Here</span><span class="cursor"></span>
		</h1>
	</div>
