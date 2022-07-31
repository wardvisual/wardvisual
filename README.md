<main class="readme-profile">
  <div class="hero">
    <!-- Banner -->
    <div class="hero__images">
        <img src="./assets/banner.svg" alt="banner"/>
        <img src="./assets/logo.svg" alt="logo"/>
    </div>
    <!-- Introduction -->
    <div>
        <h3>Hey, Great seeing you! 👋🏻</h3>
        <p> Hello, I'm Edward Fernandez. Full-Stack JS Developer based in the Philippines. </p>
    </div>
    <!-- Badges -->
    <div class="hero__user">
        <img src="https://readme-typing-svg.herokuapp.com?color=%234187FF&size=22&lines=I'm+Edward+Fernandez;Javascript+Enthusiast;UI%2FUX+Design+Engineer" />
    </div>
  </div>
</main>

<!-- Style -->
<style>
    /*Profile*/
    .readme-profile {
        display: grid;
        place-items: center;
        box-shadow: 0px 0 2em #5A9BDA inset;
        padding: 1em;
    }

    /*Hero*/
    .readme-profile .hero {
        text-align: center;
    }

    /*Hero Content*/
    .readme-profile .hero h3 {
        color: #5A9BDA;
    }

    /*Hero Images*/
    .readme-profile .hero .hero__images {
        display: grid;
        place-items: center;
        grid-gap: 2em;
    }

    .readme-profile .hero .hero__images img:last-child {
        max-width: 15em;
    }

    /* Hero GIF */
    .readme-profile .hero .hero__user {
        display: grid;
        place-items: center;
    }
    
    .readme-profile .hero .hero__user img {
        padding-left: 8em;
    }

</style>
