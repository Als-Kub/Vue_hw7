<template>
  <div>
    <footer class="footer center">
    <div class="footer__left">
      <div class="logo">
        <img
          src="@/assets/img/Main/Logo.svg"
          alt="Logo icon"
          class="logo__icon"
        />
        <p class="logo__text">Interno</p>
      </div>
      <p class="footer__text">
        It is a long established fact that a reader will be distracted lookings.
      </p>
      <a href="#" class="footer__link footer__link_margin"
        ><img src="@/assets/img/Main/footer_icon_1.svg" alt="Footer icon"
      /></a>
      <a href="#" class="footer__link"
        ><img src="@/assets/img/Main/footer_icon_2.svg" alt="Footer icon"
      /></a>
    </div>
    <div class="footer__center">
      <h3 class="footer__title">Pages</h3>
      <nav class="nav">
        <ul class="nav__ul footer__nav_flex">
          <li class="nav__li">
            <a href="#" class="nav__link footer__nav__link_font">Home</a>
          </li>
          <li class="nav__li">
            <a href="#" class="nav__link footer__nav__link_font">Project</a>
          </li>
          <li class="nav__li">
            <a href="#" class="nav__link footer__nav__link_font">Blog</a>
          </li>
        </ul>
      </nav>
    </div>
    <div class="footer__right">
      <h3 class="footer__title">Contact</h3>
      <p class="footer__text">
        55 East Birchwood Ave. Brooklyn, New York 11201
      </p>
      <p class="footer__text footer__text_lign-height">contact@interno.com</p>
      <p class="footer__text footer__text_lign-height">(123) 456 - 7890</p>
    </div>
  </footer>
  </div>
</template>

<script>
export default {};
</script>

<style scoped></style>
