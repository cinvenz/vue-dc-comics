<template>
  <footer>
    <div class="container footer">
      <div class="footer-link">
        <div>
          <p>DC COMICS</p>
          <ul>
            <li><a href="">Characters</a></li>
            <li><a href="">Characters</a></li>
            <li><a href="">Characters</a></li>
            <li><a href="">Characters</a></li>
            <li><a href="">Characters</a></li>
            <li><a href="">Characters</a></li>
            <li><a href="">Characters</a></li>
          </ul>
          <p>SHOP</p>
          <ul>
            <li><a href="">Characters</a></li>
            <li><a href="">Characters</a></li>
          </ul>
        </div>
        <div>
          <p>DC</p>
          <ul>
            <li><a href="">Characters</a></li>
            <li><a href="">Characters</a></li>
            <li><a href="">Characters</a></li>
            <li><a href="">Characters</a></li>
            <li><a href="">Characters</a></li>
            <li><a href="">Characters</a></li>
            <li><a href="">Characters</a></li>
            <li><a href="">Characters</a></li>
            <li><a href="">Characters</a></li>
            <li><a href="">Characters</a></li>
            <li><a href="">Characters</a></li>
          </ul>
        </div>
        <div>
          <p>SITES</p>
          <ul>
            <li><a href="">Characters</a></li>
            <li><a href="">Characters</a></li>
            <li><a href="">Characters</a></li>
            <li><a href="">Characters</a></li>
            <li><a href="">Characters</a></li>
          </ul>
        </div>
      </div>
    </div>
    <div class="socials">
      <div class="container">
        <button></button>
        <div>
          <p>FOLLOW US</p>
        </div>
      </div>
    </div>
  </footer>
</template>

<script>
export default {
  name: 'FooterPage',
};
</script>

<style lang="scss" scoped>
  footer {
    height: 42vh;
    background-image: url(@/footer-bg.jpg);
    background-position: top;
    background-repeat: no-repeat;
    background-size: cover;
    .footer {
      display: flex;
      align-items: center;
      background-image: url(@/dc-logo-bg.png);
      background-position: right;
      background-repeat: no-repeat;
      background-size: 25rem;
      .footer-link {
      display: flex;
      gap: 3rem;
      li {
        list-style: none;
        a {
          text-decoration: none;
          color: #959595;
        }
      }
      }
    }
    p {
      color: white;
      margin-bottom: .5rem;
      margin-top: .8rem;
      font-size: 1rem;
    }
  }
</style>
