<template>
  <header>
    <div class="container">
      <nav>
        <img class="logo-dc" src="../../public/dc-logo.png" alt="DC Logo" />
        <ul>
          <li><a href="#!">CHARACTERS</a></li>
          <li><a href="#!">COMICS</a></li>
          <li><a href="#!">MOVIES</a></li>
          <li><a href="#!">TV</a></li>
          <li><a href="#!">GAMES</a></li>
          <li><a href="#!">COLLECTIBLES</a></li>
          <li><a href="#!">VIDEOS</a></li>
          <li><a href="#!">FANS</a></li>
          <li><a href="#!">NEWS</a></li>
          <li><a href="#!">SHOP</a></li>
        </ul>
      </nav>
    </div>
  </header>
</template>

<script>
export default {
  name: "HeaderPage",
};
</script>

<style lang="scss" scoped>
header {
  text-align: center;
  height: 6rem;
  font-size: 0.6rem;
  font-weight: bold;
  nav {
    display: flex;
    justify-content: space-between;
    align-items: center;
    height: 100%;
    .logo-dc {
      width: 4rem;
      cursor: pointer;
    }
    ul {
      display: flex;
      justify-content: center;
      height: 100%;
      list-style: none;
      gap: 0.5rem;
      a {
        text-decoration: none;
        color: #4d5661;
        display: flex;
        justify-content: center;
        align-items: center;
        padding: 0 0.5rem;
        height: 100%;
        &:hover {
          border-top: 3px solid white;
          border-bottom: 3px solid #0282f9;
          color: #0282f9;
        }
      }
    }
  }
}
</style>
