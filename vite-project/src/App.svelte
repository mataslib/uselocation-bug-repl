<script>
  import {Router, Link, Route} from "svelte-navigator";
  import NotWorkingPage from './NotWorkingPage.svelte';
  import WorkingPage from './WorkingPage.svelte';
</script>

<main>
  <Router>
    <Link to="error">
      error route (useLocation())
    </Link>
    <br>
    <Link to="working">
      working route
    </Link>
    <br>
    <Route path="error" component={NotWorkingPage} />
    <Route path="working" component={WorkingPage} />
  </Router>
</main>
