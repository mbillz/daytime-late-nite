<main>
	<div class="bg" />
	<h1>daytime late nite is a feeling.</h1>
</main>

<style>
	main {
		align-items: center;
		height: 100vh;
		display: flex;
		justify-content: center;
		text-align: center;
	}

	@keyframes bgColor {
		0% {
			background-color: #048a81;
		}
		25% {
			background-color: #06d6a0;
		}
		50% {
			background-color: #54c6eb;
		}
		75% {
			background-color: #8a89c0;
		}
		100% {
			background-color: #cda2ab;
		}
	}

	.bg {
		animation: bgColor 20000ms infinite alternate;
		bottom: 0;
		left: 0;
		position: absolute;
		right: 0;
		top: 0;
		z-index: -1;
	}

	h1 {
		font-size: 2.5rem;
	}
</style>
