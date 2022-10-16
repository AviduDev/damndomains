<script>
	import Categories from '$lib/categories.svelte';
	import DomainCard from '$lib/domainCard.svelte';
</script>

<main class="main">
	<h1>domains</h1>
	<Categories />
	<section class="section">
		<div class="product-ctn">
			<img class="product-img" src="placeholder.svg" alt="" />
			<h2>name of the domain</h2>
			<div class="btn-ctn">
				<p>000.00$</p>
				<img class="cart-icon" src="cart.svg" alt="add to cart button" />
			</div>
		</div>
	</section>
</main>

<style>
	h1 {
		text-align: center;
	}
	.product-img {
		width: 100%;
		aspect-ratio: 16 / 9;
	}

	.cart {
		cursor: pointer;
	}
	.cart-icon {
		width: 50px;
	}

	.product-ctn {
		background-color: #ffeb80;
		border: solid black 3px;
		border-radius: 10px;
	}

	.product-img {
		border: solid black 2px;
		border-radius: 100px;
	}

	h2 {
		background-color: #fff;
		color: black;
		padding: 1vw;
		border: solid black 2px;
		border-radius: 10px;
		text-align: center;
		margin: 10px;
	}

	.btn-ctn {
		display: grid;
		grid-template-columns: 1fr 1fr;
        justify-items: flex-end;
		width: 100%;
		height: 100%;
	}

	.product-ctn {
		display: flex;
		flex-direction: column;
		align-items: center;
		justify-content: center;
		padding: 10px;
	}

	.btn-ctn p {
        display: flex;
        justify-content: center;
        align-items: center;
		border: solid black 2px;
		border-radius: 10px;
		background-color: #c4fff9;
		width: 100%;
		height: 100%;
		text-align: center;
	}

	.btn-ctn img {
		border: solid black 2px;
		border-radius: 10px;
		background-color: #3596ff;
	}
</style>
