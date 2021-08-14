<script>
	let x = 21;
	let y = 20;

	$: if (x < 0) {
		x = 0;
	}

	$: if (y < 0) {
		y = 0;
	}
</script>



<main>
	<section class="hero is-danger">
		<div class="hero-body">
		  <p class="title has-text-centered">
			Multi-Calc
		  </p>
		</div>
	  </section>
	  <br>
	<div class="container">
		<label for="num">Numero Um:</label>
		<input bind:value={x} class="input m-3" type="number" name="num">

		<label for="ndois">Numero Dois:</label>
		<input bind:value={y} class="input m-3" type="number" name="ndois">

	</div>

	<div class="has-text-centered">
		<div class="box m-3 content">
			<ul>
				<li>Soma: {x + y}</li>
				<div class="m-2">
					{#if x + y == 420}
					<p>IIIHHH CARAI TO LOMBRADO KKKKKKKKK!!!1!!</p>
					{/if}
					
					{#if x + y == 69}
					<p>HMMM SEXO.</p>
					{/if}
					
					{#if x + y == 50135}
					<p>Aqui não é um local onde se procura seios. Clique para ver seios <a href="https://www.youtube.com/watch?v=QtBDL8EiNZo">aqui</a>.</p>
					{/if}
					
					{#if x + y == 58008}
					<p>Aqui não é um local onde se procura boobs. Clique para ver boobs <a href="https://www.youtube.com/watch?v=QtBDL8EiNZo">aqui</a>.</p>
					{/if}
					
					{#if x + y == 24}
					<p>Ih! Ah, lá! Veadão!</p>
					{/if}

					{#if x + y == 42}
					<p>Compreendo, você conhece a resposta da vida, universo e muito mais.</p>
					{/if}

					{#if x + y == 550}
					<p>Eu sei, falta um "0" para formar <i>OSSO</i></p>
					{/if}
				</div>
			</ul>
		</div>
		<div class="box m-3 content">
			<ul>
				<li>Subtração: {x - y}</li>
				<div class="m-2">
					{#if x - y == 420}
					<p>IIIHHH CARAI TO LOMBRADO KKKKKKKKK!!!1!!</p>
					{/if}
					
					{#if x - y == 69}
					<p>HMMM SEXO.</p>
					{/if}
					
					{#if x - y == 50135}
					<p>Aqui não é um local onde se procura seios. Clique para ver seios <a href="https://www.youtube.com/watch?v=QtBDL8EiNZo">aqui</a>.</p>
					{/if}
					
					{#if x - y == 58008}
					<p>Aqui não é um local onde se procura boobs. Clique para ver boobs <a href="https://www.youtube.com/watch?v=QtBDL8EiNZo">aqui</a>.</p>
					{/if}
					
					{#if x - y == 24}
					<p>Ih! Ah, lá! Veadão!</p>
					{/if}

					{#if x - y == 42}
					<p>Compreendo, você conhece a resposta da vida, universo e muito mais.</p>
					{/if}

					{#if x - y == 550}
					<p>Eu sei, falta um "0" para formar <i>OSSO</i></p>
					{/if}
				</div>
			</ul>
		</div>
		<div class="box m-3 content">
			<ul>
				<li>Multiplicação: {x * y}</li>
				<div class="m-2">
					{#if x * y == 420}
					<p>IIIHHH CARAI TO LOMBRADO KKKKKKKKK!!!1!!</p>
					{/if}
					
					{#if x * y == 69}
					<p>HMMM SEXO.</p>
					{/if}
					
					{#if x * y == 50135}
					<p>Aqui não é um local onde se procura seios. Clique para ver seios <a href="https://www.youtube.com/watch?v=QtBDL8EiNZo">aqui</a>.</p>
					{/if}
					
					{#if x * y == 58008}
					<p>Aqui não é um local onde se procura boobs. Clique para ver boobs <a href="https://www.youtube.com/watch?v=QtBDL8EiNZo">aqui</a>.</p>
					{/if}
					
					{#if x * y == 24}
					<p>Ih! Ah, lá! Veadão!</p>
					{/if}

					{#if x * y == 42}
					<p>Compreendo, você conhece a resposta da vida, universo e muito mais.</p>
					{/if}

					{#if x * y == 550}
					<p>Eu sei, falta um "0" para formar <i>OSSO</i></p>
					{/if}
				</div>
			</ul>
		</div>
		<div class="box m-3 content">
			<ul>
				<li>Divição: {x / y}</li>
				<div class="m-2">
					{#if x / y == 420}
					<p>IIIHHH CARAI TO LOMBRADO KKKKKKKKK!!!1!!</p>
					{/if}
					
					{#if x / y == 69}
					<p>HMMM SEXO.</p>
					{/if}
					
					{#if x / y == 50135}
					<p>Aqui não é um local onde se procura seios. Clique para ver seios <a href="https://www.youtube.com/watch?v=QtBDL8EiNZo">aqui</a>.</p>
					{/if}
					
					{#if x / y == 58008}
					<p>Aqui não é um local onde se procura boobs. Clique para ver boobs <a href="https://www.youtube.com/watch?v=QtBDL8EiNZo">aqui</a>.</p>
					{/if}
					
					{#if x / y == 24}
					<p>Ih! Ah, lá! Veadão!</p>
					{/if}

					{#if x / y == 42}
					<p>Compreendo, você conhece a resposta da vida, universo e muito mais.</p>
					{/if}

					{#if x / y == 550}
					<p>Eu sei, falta um "0" para formar <i>OSSO</i></p>
					{/if}
				</div>
			</ul>
		</div>
	</div>
</main>
<hr>
<footer class="footer">
	<div class="content has-text-centered">
	  <p>
		<strong>Multi-Calc</strong> by <a href="https://github.com/gionneves">Giovanni Neves Sadauscas</a> <br>
		project made with <a href="https://svelte.dev/">Svelte</a> and <a href="https://bulma.io/">Bulma</a>.
	  </p>
	</div>
  </footer>