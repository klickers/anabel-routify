
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
            <a href = "https://www.linkedin.com/in/anabel-chen-77839918b/"><i class="fab fa-linkedin"></i></a>
        </div>
    </div>
</nav>


<!-- Background, upper half -->
<div class = "ab-background"></div>


<!-- Main Content -->
<main>
    <!-- Profile picture -->
    <img alt = "Anabel's profile picture" class = "ab-profile-pic" src = "https://media-exp1.licdn.com/dms/image/C5603AQEDXTO5cHgzZQ/profile-displayphoto-shrink_200_200/0?e=1592438400&v=beta&t=oCzF-NOa3Q_MIib8sX_D2vPKEx6mQFnpulBtLzf8GII" />

    <slot />
</main>


<!-- Footer -->
<footer>
    <p>Crafted with &#x1F499; by <a href = "#https://github.com/klickers" target = "_blank">klickers</a></p>
</footer>

<!-- scripts go here -->
