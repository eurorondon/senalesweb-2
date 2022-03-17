<script>
	import { Router, Route, Link, link } from "Svelte-routing";
	import Home from "./Home.svelte";
</script>

<Router>
	<div>
		<Route path="/" component={Home} />
	</div>
</Router>
