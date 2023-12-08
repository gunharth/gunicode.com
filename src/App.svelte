<main>
	<h1 data-text="{'{'}g{'}'}unicode">{'{'}g{'}'}unicode</h1>
	<h2>DESIGN LED TECHNOLOGY</h2>
	<div><a href="&#109;&#97;&#105;&#108;&#116;&#111;&#58;&#111;&#102;&#102;&#105;&#99;&#101;&#64;&#103;&#117;&#110;&#105;&#99;&#111;&#100;&#101;&#46;&#99;&#111;&#109;">&#111;&#102;&#102;&#105;&#99;&#101;&#64;&#103;&#117;&#110;&#105;&#99;&#111;&#100;&#101;&#46;&#99;&#111;&#109;</a></div>
</main>

<style>
	main {
		display: flex;
		min-height: 100vh;
		align-items: center;
		justify-content: center;
		flex-direction: column;
	}

	h1 {
		position: relative;
		font-size: 48px;
		letter-spacing: 0.07em;
		margin: 0;
		padding: 0;
		font-weight: 300;
		font-style: normal;
		color: #000;
	}

	h1::before {
		content: attr(data-text);
		position: absolute;
		top: 0;
		left: 0;
		width: 100%;
		color: #fff;
		animation: reveal 2s linear;
		overflow: hidden;
	}

	@keyframes reveal {
		0% {
			width: 0;
		}

		100% {
			width: 100%;
		}
	}


	h2 {
		font-size: 16px;
		letter-spacing: 2px;
		margin-top: 4px;
		padding: 0;
		font-weight: 300;
		font-style: normal;
		animation: show 2s linear;
		animation-fill-mode: forwards;
		animation-delay: 2.5s;
		opacity: 0;
	}

	@keyframes show {
		100% {
			opacity: 1;
		}
	}

	div {
		margin-top: 6em;
		animation: show 2s linear;
		animation-fill-mode: forwards;
		animation-delay: 4s;
		opacity: 0;
	}
</style>
