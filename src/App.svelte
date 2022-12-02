<!-- App.svelte -->
<script>
  import { Router, Link, Route } from "svelte-routing";
  import Home from "./routes/Home.svelte";
  import Settings from "./routes/settings.svelte"

  export let url = "";
</script>

<Router url="{url}">
  <div>
    <Route path="/"><Home /></Route>
    <Route path="/settings"><Settings /></Route>
  </div>
</Router>