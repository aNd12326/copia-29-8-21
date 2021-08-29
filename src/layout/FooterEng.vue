<template>
  <footer
    class="footer"
    :class="{ [`footer-${type}`]: type }"
    :data-background-color="backgroundColor"
  >
    <div class="container">
      <div class="section section-team text-center" id="chcolor">
        <div class="container">
          <h3 class="title pb-2">or contact us by</h3>
            <div class="row pt-4">
              <div class="col-md-3">
                <div>
                  <i class="far fa-phone-alt fa-2x"></i>
                  <p class="pt-3">(+571) 786 866</p>
                </div>
              </div>
              <div class="col-md-3">
                <div>
                  <i class="far fa-envelope fa-2x"></i>
                  <p class="pt-3">sales2@kasda.com</p>
                </div>
              </div>
              <div class="col-md-3">
                <div>
                  <i class="fal fa-map-marker-alt fa-2x"></i>
                  <p class="pt-3">Street 932 N° 15 - 23 of 401 <br> Usa - ottawa</p>
                </div>
              </div>
              <div class="col-md-3">
                  <div>
                  <i class="fal fa-clock fa-2x"></i>
                  <p class="pt-3">Monday - Friday <br> 7:20 am - 5:30 pm</p>
                  </div>
              </div>
            </div>
      </div>
    </div>

      <nav class="pt-4">
        <ul>
          <li class="nav-item">
            <a
              class="nav-link"
              rel="tooltip"
              title="Like us on Facebook"
              data-placement="bottom"
              href="https://www.facebook.com/CreativeTim"
              target="_blank"
            >
              <i class="fab fa-facebook-square fa-2x" id="mediasocials"></i>
              <p class="d-lg-none d-xl-none">Facebook</p>
            </a>
          </li>
          <li class="nav-item">
            <a
              class="nav-link"
              rel="tooltip"
              title="Follow us on Twitter"
              data-placement="bottom"
              href="https://twitter.com/CreativeTim"
              target="_blank"
            >
              <i class="fab fa-twitter fa-2x" id="mediasocials"></i>
              <p class="d-lg-none d-xl-none">Twitter</p>
            </a>
          </li>
          <li class="nav-item">
            <a
              class="nav-link"
              rel="tooltip"
              title="Follow us on Instagram"
              data-placement="bottom"
              href="https://www.instagram.com/CreativeTimOfficial"
              target="_blank"
            >
              <i class="fab fa-instagram fa-2x" id="mediasocials"></i>
              <p class="d-lg-none d-xl-none">Instagram</p>
            </a>
          </li>
        </ul>
      </nav>
      <div class="copyright">
        &copy; {{ year }}
      </div>
    </div>
  </footer>
</template>
<script>
export default {
  props: {
    backgroundColor: String,
    type: String,
  },
  data() {
    return {
      year: new Date().getFullYear(),
    };
  },
};
</script>
<style></style>

