<template>
  <header>
    <div class="container">
      <nav>
        <img class="logo-dc" src="@/dc-logo.png" alt="DC Logo">
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
  name: 'HeaderPage',
};
</script>

<style lang="scss" scoped>
  header {
    text-align: center;
    height: 14vh;
    background-color: gainsboro;
    nav {
      display: flex;
      justify-content: space-between;
      align-items: center;
      height: 100%;
      .logo-dc {
        width: 3.5rem;
      }
      ul {
        display: flex;
        justify-content: center;
        height: 100%;
        list-style: none;
        a {
          text-decoration: none;
          color: #4D5661;
          display: flex;
          justify-content: center;
          align-items: center;
          padding: 0 .5rem;
          height: 100%;
          &:hover {
            background-color: aquamarine;
          }
        }
      }
    }
  }
</style>
