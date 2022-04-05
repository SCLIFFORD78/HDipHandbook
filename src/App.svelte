<script>
  import Main from "./pages/Main.svelte"
  import Navigator from "./components/Navigator.svelte";
  import Router from "svelte-spa-router";


  let routes = {
    "/": Main,
  }
</script>

<div class="uk-container">
  <Navigator/>
  <Router {routes}/>
</div>
