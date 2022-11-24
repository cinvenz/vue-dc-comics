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
  <div class="footer-socials">
      <div class="container social-icon">
        <div>
          <button>SIGN-UP NOW!</button>
        </div>
        <div class="icon">
          <p>FOLLOW US</p>
          <img src="@/footer-facebook.png" alt="">
          <img src="@/footer-twitter.png" alt="">
          <img src="@/footer-youtube.png" alt="">
          <img src="@/footer-pinterest.png" alt="">
          <img src="@/footer-periscope.png" alt="">
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
    .footer-socials {
      background-color: #303030;
      height: 12vh;
      .social-icon {
        display: flex;
        align-items: center;
        justify-content: space-between;
        .icon {
          display: flex;
          align-items: center;
          gap: 1rem;
          p {
            color: #0282F9;
          }
          img {
            width: 1.5rem;
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
