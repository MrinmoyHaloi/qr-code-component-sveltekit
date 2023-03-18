<div class="container">
	<div class="qr-component">
		<img src="image-qr-code.png" alt="qr code" />
		<div class="text">
			<h1>Improve your front-end skills by building projects</h1>
			<p>Scan the QR code to visit Frontend Mentor and take your coding skills to the next level</p>
		</div>
	</div>
	<div class="attribution">
		Challenge by <a href="https://www.frontendmentor.io?ref=challenge" target="_blank"
			>Frontend Mentor</a
		>. Programmed by <a href="https://mrinmoy.is-a.dev">Mrinmoy Haloi</a>.
	</div>
</div>

<style lang="scss">
	.container {
		background-color: hsl(212, 45%, 89%);
		height: 100vh;
		width: 100vw;
		padding: 1rem;
		display: grid;
		place-items: center;

		.qr-component {
			background-color: hsl(0, 0%, 100%);
			max-width: 16rem;
			padding: 0.8rem;
			border-radius: 1rem;
			text-align: center;
			box-shadow: 0px 10px 20px 0px rgba(0, 0, 0, 0.1);

			img {
				width: 100%;
				object-fit: cover;
				border-radius: 0.5rem;
			}

			.text {
				padding: 0.5rem;
				h1 {
					font-size: 1.1rem;
					font-weight: 700;
					margin-block: 0.8rem;
					color: hsl(218, 44%, 22%);
				}

				p {
					font-size: 12px;
					margin-bottom: 0.7rem;
					padding-inline: 0.1rem;
					color: hsl(220, 15%, 55%);
				}
			}
		}
	}

	.attribution {
		font-size: 12px;
		position: absolute;
		bottom: 2rem;
		right: 2rem;
        padding: 1rem;
	}
	.attribution a {
		color: hsl(214, 68%, 45%);
		text-decoration: none;
	}
</style>
