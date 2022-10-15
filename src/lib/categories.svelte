<script></script>

<section>
	<div class="grid">
		<div class="grid-item">
			<a href="#end">
				<img src="image.jpg" alt="domain category" />
				<h2 class="cat-name"><span class="bold">business</span><br />omains</h2>
			</a>
		</div>
		<div class="grid-item">
			<a href="/">
				<img src="image.jpg" alt="domain category" />
				<h2 class="cat-name"><span class="bold">personal</span><br />domains</h2>
			</a>
		</div>
		<div class="grid-item">
			<a href="/">
				<img src="image.jpg" alt="domain category" />
				<h2 class="cat-name"><span class="bold">niche</span><br />domains</h2>
			</a>
		</div>
		<div class="grid-item">
			<a href="/">
				<img src="image.jpg" alt="domain category" />
				<h2 class="cat-name"><span class="bold">funny</span><br />domains</h2>
			</a>
		</div>
	</div>
</section>

<style>
	* {
		font-family: 'inter';
	}

    * {
        scroll-behavior: smooth;
    }
	img {
		width: 100%;
	}

	.grid {
		display: grid;
		grid-template-columns: 1fr;
		grid-auto-flow: row;
		max-width: 100vw;
		justify-items: center;
	}

	.grid-item {
		display: flex;
		flex-direction: column;
		align-items: center;
		justify-content: center;
		text-align: center;
		background-color: #c4fff9;
		margin-top: 10px;
		padding: 20px;
		border: solid black 3px;
		border-radius: 10px;
	}

	img {
		border: solid 2px black;
		border-radius: 100px;
	}

	.bold {
		font-weight: 900;
		font-size: 10vw;
	}

	.cat-name {
		font-size: 5vw;
	}
</style>
