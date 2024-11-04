<script lang="ts">
	import '../app.css';
	let { children } = $props();
</script>

<!-- <main> Navigation -->
	<!-- <nav>
		<ul> 
			<li><a href="/">home</a></li>
			<li><a href="/">portfolio</a></li>
			<li><a href="/">about</a></li>
			<li><a href="/">contact</a></li>
		</ul>
	</nav>  -->
	{@render children()}
  <!-- </main> -->

