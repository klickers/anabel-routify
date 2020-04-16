
<!-- src/pages/recipes/cakes/cupcakes.svelte -->
<script>
  import { url } from '@sveltech/routify'
</script>
<!-- Navigation Menu -->
<nav>
    <div class = "ab-nav-item">
        <a href = { $url('/index') }>Home</a>
    </div>
    <div class = "ab-nav-item">
        <a href = { $url('/resume') }>Résumé</a>
    </div>
    <div class = "ab-nav-social">
        <div class = "ab-nav-item">
            <a href = "https://www.linkedin.com/in/anabel-chen-77839918b" target="_blank"><i class="fab fa-linkedin"></i></a>
        </div>
    </div>
</nav>


<!-- Background, upper half -->
<div class = "ab-background"></div>


<!-- Main Content -->
<main>
    <!-- Profile picture -->
    <img alt = "Anabel's profile picture" class = "ab-profile-pic" src = "/anabel.jpg" />

    <slot />
</main>


<!-- Footer -->
<footer>
    <p>Crafted with &#x1F499; by <a href = "#https://github.com/klickers" target = "_blank">klickers</a></p>
</footer>

<!-- scripts go here -->
