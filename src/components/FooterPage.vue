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
          <img src="../../public/footer-facebook.png" alt="" />
          <img src="../../public/footer-twitter.png" alt="" />
          <img src="../../public/footer-youtube.png" alt="" />
          <img src="../../public/footer-pinterest.png" alt="" />
          <img src="../../public/footer-periscope.png" alt="" />
        </div>
      </div>
    </div>
  </footer>
</template>

<script>
export default {
  name: "FooterPage",
};
</script>

<style lang="scss" scoped>
footer {
  height: 16rem;
  background-image: url(../../public/footer-bg.jpg);
  background-position: top;
  background-repeat: no-repeat;
  background-size: cover;
  .footer {
    display: flex;
    align-items: center;
    background-image: url(../../public/dc-logo-bg.png);
    background-position: right;
    background-repeat: no-repeat;
    background-size: 25rem;
    padding-bottom: 1rem;
    .footer-link {
      display: flex;
      gap: 3rem;
      font-size: 0.6rem;
      li {
        list-style: none;
        margin-top: 0.3rem;
        &:hover {
          text-decoration: underline;
        }
        a {
          text-decoration: none;
          color: #959595;
        }
      }
    }
  }
  .footer-socials {
    background-color: #303030;
    height: 5rem;
    .social-icon {
      display: flex;
      align-items: center;
      justify-content: space-between;
      .icon {
        display: flex;
        align-items: center;
        gap: 1rem;
        p {
          color: #0282f9;
        }
        img {
          width: 1.5rem;
        }
      }
    }
  }
  p {
    color: white;
    margin-bottom: 0.5rem;
    margin-top: 0.8rem;
    font-size: 1rem;
  }
  button {
    padding: 0.5rem 1rem;
    border: 2px solid #0282f9;
    background-color: #303030;
    color: white;
    font-weight: bold;
    cursor: pointer;
    &:hover {
      color: #0282f9;
    }
  }
}
</style>
