<script>
  //pages
	import Login from './pages/Login.svelte'
  import Checkout from './pages/Checkout.svelte'
  import Home from './pages/Home.svelte'

  //
  import { Router, Route, Link } from 'svelte-routing'

</script>

<Router>
  <nav class="navbar">
    <Link to = '/'>Home</Link>
    <Link to = '/'>Menu</Link>
    <Link to = '/'>About</Link>
  </nav>

  <Route path ="/" component= {Home} />
<!--   <Route path ="/login" component= {Login} /> -->
</Router>
