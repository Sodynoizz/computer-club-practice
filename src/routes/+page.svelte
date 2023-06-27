<svelte:head>
  <style>
    @import url('https://fonts.googleapis.com/css2?family=Kanit:wght@300&display=swap');
    body {
        font-family: 'Kanit', sans-serif;
    }
  </style>
</svelte:head>

<script>
    const navlinks = [
        { name: "Practice", path: "/practice"},
    ];
</script>

<div id="container">
    <h1>Computer Club Triamudom Launchpad</h1>
    <h2>All routes</h2>
    <nav>
        { #each navlinks as link }
            <div class="routes">
                <li><a href="{link.path}">{link.name}</a></li>
            </div>
        { /each }
    </nav>
</div>

<style>
    h1 {
        text-align: center;
    }
    
    h2 {
        text-align: center;
    }

    .routes {
        text-align: center;
    }

    .routes a {
        text-decoration: none;
    }

</style>