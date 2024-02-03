<script>
export default {
  name: 'AppHeader',


}
</script>
<template>
  <header>

    <nav class="container">
      <div class="logo">
        <img src="/img/dc-logo.png" alt="">
      </div>
      <ul>
        <li><a href="">Characters</a></li>
        <li><a href="">Comics</a></li>
        <li><a href="">Movies</a></li>
        <li><a href="">TV</a></li>
        <li><a href="">Games</a></li>
        <li><a href="">Collectibles</a></li>
        <li><a href="">Videos</a></li>
        <li><a href="">Fans</a></li>
        <li><a href="">News</a></li>
        <li><a href="">Shop</a></li>
      </ul>
    </nav>
  </header>
</template>
<style scoped>
header
{
  background-color: var(--dc-light);

  & nav
  {
    display: flex;
    flex-wrap: wrap;
    justify-content: space-between;
    align-items: center;

  }

  & .logo > img
  {

    width: 70px;
  }

  & ul
  {
    display: flex;
    gap: 1rem;

    & > li {
      padding: 2rem 0;
      border-bottom: 4px solid transparent;

      & > a {
        color: var(--dc-secondary);
        font-weight: 600;
      }
    }

   & > li:hover {
      border-bottom: 4px solid var(--dc-primary);
    }

  }

}
</style>