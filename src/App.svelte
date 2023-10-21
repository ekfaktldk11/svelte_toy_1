<script>
  import { Router, Link, Route } from 'svelte-routing';
  import Home from './client/home/home.svelte';
  import LeaderBoard from './client/LeaderBoard/leaderBoard.svelte';
  import Profile from './client/Profile/profile.svelte';
  import NavButton from './client/NavButton.svelte';

  export let url = '';
</script>

<main class="main">
  <Router {url}>
    <div class="nav">
      <nav class="btn-container">
        <Link to="/">
          <NavButton titleName="Home" />
        </Link>
        <Link to="/profile">
          <NavButton titleName="MyProfile" />
        </Link>
        <Link to="/leaderboard">
          <NavButton titleName="LeaderBoard" />
        </Link>
      </nav>
    </div>
    <div>
      <Route path="/" component={Home} />
      <Route path="/leaderboard" component={LeaderBoard} />
      <Route path="/profile" component={Profile} />
    </div>
  </Router>
</main>

<style>
  .main {
    z-index: 1;
  }

  .nav {
    display: flex;
    position: fixed;
    width: 100%;
    height: 5rem;
    z-index: 3;
    background-color: white;
    border-bottom: 0.1rem #abb8c3 solid;
  }

  .btn-container {
    display: flex;
    flex-direction: row;
    position: absolute;
    top: 1em;
    right: 1em;
    position: fixed;
    background-color: white;
  }
</style>
