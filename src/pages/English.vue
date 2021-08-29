<template>
  <div>
    <div id="home" class="page-header page-header-small">
      <parallax
        class="page-header-image"
        style="background-image: url('img/fotos/_MG_8305-p.jpg')"
      >
      </parallax>
      <div class="content-center">
        <div class="container">
          <!-- <h4 class="title">Remediación de suelos con técnicas y tecnologías de vanguardia en Perú,bajo un enfoque innovador, eficientey muy respetuoso del medioambiente.  </h4> -->
          <div class="banner">
            <h4>Soil remediation 
              <span class="typed-text">{{ typeValue }}</span>
              <span class="cursor" :class="{ 'typing': typeStatus}">&nbsp;</span>
            </h4>
          </div>

          <div class="text-center">
            <a href="#pablo" class="btn btn-primary btn-icon btn-round">
              <i class="fab fa-facebook-square"></i>
            </a>
            <a href="#pablo" class="btn btn-primary btn-icon btn-round">
              <i class="fab fa-twitter"></i>
            </a>
            <a href="#pablo" class="btn btn-primary btn-icon btn-round">
              <i class="fab fa-google-plus"></i>
            </a>
          </div>
        </div>
      </div>
    </div>
    <div id="about" class="section section-about-us">
      <div class="container pb-1">
        <div class="row">
          <div class="col-md-8 ml-auto mr-auto text-center">
            <h2 class="title">About Us</h2>
            <!-- <h5 class="description"></h5> -->
          </div>
        </div>
        <div class="separator separator-primary"></div>
        <div class="section-story-overview pt-3">
          <div class="row">
            <div class="col-md-6">
              <div
                class="image-container image-left"
                style="
                  background-image: url('img/fotos/CSUR 23_03-05-08 (26).jpg');
                "
              >
                <!-- First image on the left side -->
                <p class="blockquote blockquote-primary">
                  "Over the span of the satellite record, Arctic sea ice has
                  been declining significantly, while sea ice in the
                  Antarctichas increased very slightly"
                  <br />
                  <br />
                  <small>-NOAA</small>
                </p>
              </div>
              <!-- Second image on the left side of the article -->
              <div
                class="image-container"
                style="background-image: url('img/fotos/P_20170818_063218.jpg')"
              ></div>
            </div>
            <div class="col-md-5">
              <!-- First image on the right side, above the article -->
              <div
                class="image-container image-right"
                style="
                  background-image: url('img/fotos/IMG_20180226_095316.jpg');
                "
              ></div>
              <h3 class="pt-3">Nuestra Mision</h3>
              <p>
                The Arctic Ocean freezes every winter and much of the sea-ice
                then thaws every summer, and that process will continue whatever
                happens with climate change. Even if the Arctic continues to be
                one of the fastest-warming regions of the world, it will always
                be plunged into bitterly cold polar dark every winter. And
                year-by-year, for all kinds of natural reasons, there’s huge
                variety of the state of the ice.
              </p>
              <p>
                For a start, it does not automatically follow that a record
                amount of ice will melt this summer. More important for
                determining the size of the annual thaw is the state of the
                weather as the midnight sun approaches and temperatures rise.
                But over the more than 30 years of satellite records, scientists
                have observed a clear pattern of decline, decade-by-decade.
              </p>
              <p>
                The Arctic Ocean freezes every winter and much of the sea-ice
                then thaws every summer, and that process will continue whatever
                happens with climate change. Even if the Arctic continues to be
                one of the fastest-warming regions of the world, it will always
                be plunged into bitterly cold polar dark every winter. And
                year-by-year, for all kinds of natural reasons, there’s huge
                variety of the state of the ice.
              </p>
            </div>
          </div>
        </div>
      </div>
    </div>
    <div id="services" class="section section-team text-center">
      <div class="container">
        <h2 class="title pb-3">Nuestros Servicios Word Class</h2>
        <div class="team">
          <div class="row">
            <div class="col-md-4">
                <img
                  src="img/fotos/_MG_7221.jpg"
                  alt="Thumbnail Image"
                />
                <h4 class="title">Servicio A</h4>
                <!-- <p class="category text-primary">Model</p> -->
                <p class="description">
                  You can write here details about one of your team members. You
                  can give more details about what they do. Feel free to add
                  some <a href="#">links</a> for people to be able to follow
                  them outside the site.
                </p>
                <a href="#pablo" class="btn btn-primary btn-icon btn-round"
                  ><i class="fab fa-twitter"></i
                ></a>
                <a href="#pablo" class="btn btn-primary btn-icon btn-round"
                  ><i class="fab fa-instagram"></i
                ></a>
                <a href="#pablo" class="btn btn-primary btn-icon btn-round"
                  ><i class="fab fa-facebook-square"></i
                ></a>
            </div>
            <div class="col-md-4">
                <img
                  src="img/fotos/_MG_7310.jpg"
                  alt="Thumbnail Image"
                />
                <h4 class="title">Servicio B</h4>
                <!-- <p class="category text-primary">Designer</p> -->
                <p class="description">
                  You can write here details about one of your team members. You
                  can give more details about what they do. Feel free to add
                  some <a href="#">links</a> for people to be able to follow
                  them outside the site.
                </p>
                <a href="#pablo" class="btn btn-primary btn-icon btn-round"
                  ><i class="fab fa-twitter"></i
                ></a>
                <a href="#pablo" class="btn btn-primary btn-icon btn-round"
                  ><i class="fab fa-linkedin"></i
                ></a>
            </div>
            <div class="col-md-4">
                <img
                  src="img/fotos/_MG_7221.jpg"
                  alt="Thumbnail Image"
                />
                <h4 class="title">Servicio C</h4>
                <!-- <p class="category text-primary">Fashion</p> -->
                <p class="description">
                  You can write here details about one of your team members. You
                  can give more details about what they do. Feel free to add
                  some <a href="#">links</a> for people to be able to follow
                  them outside the site.
                </p>
                <a href="#pablo" class="btn btn-primary btn-icon btn-round"
                  ><i class="fab fa-google-plus"></i
                ></a>
                <a href="#pablo" class="btn btn-primary btn-icon btn-round"
                  ><i class="fab fa-youtube"></i
                ></a>
                <a href="#pablo" class="btn btn-primary btn-icon btn-round"
                  ><i class="fab fa-twitter"></i
                ></a>
            </div>
          </div>
        </div>
      </div>
    </div>

    <div id="contact" class="section section-contact-us text-center">
      <div class="container">
        <h2 class="title text-dark">Do you have a neecesity??</h2>
        <p class="text-dark">
          Nuestros expertos encontrarán las mejores soluciones,
          <br />contáctenos y lo llamaremos en 24 horas
        </p>
        <!-- <div class="send-button">
          <n-button type="warning">Contactenos </n-button>
        </div> -->

        <h3 class="title font-weight-light">Contácta a REMEDIAPERU</h3>
        <!-- <p class="description">Remedia Perú.</p> -->
        <div class="row">
          <div class="col-lg-6 text-center ml-auto mr-auto col-md-8">
            <fg-input
              class="input-lg"
              placeholder="Nombre Completo..."
              v-model="form.firstName"
              addon-left-icon="now-ui-icons users_circle-08"
            >
            </fg-input>
            <!-- <fg-input
              class="input-lg"
              placeholder="Apellidos..."
              v-model="form.LastName"
              addon-left-icon="now-ui-icons users_circle-08"
            >
            </fg-input> -->
            <fg-input
              class="input-lg"
              placeholder="Correo Electronico..."
              v-model="form.email"
              addon-left-icon="now-ui-icons ui-1_email-85"
            >
            </fg-input>
            <fg-input
              class="input-lg"
              placeholder="Teléfono..."
              v-model="form.email"
              addon-left-icon="far fa-phone-alt fa-2x"
            >
            </fg-input>
            <div class="textarea-container">
              <textarea
                class="form-control"
                name="name"
                rows="4"
                cols="80"
                v-model="form.message"
                placeholder="Escribe un Mensaje..."
              ></textarea>
            </div>
            <div class="send-button">
              <n-button id="botonprl" round block size="lg"
                >Enviar Mensaje</n-button
              >
            </div>
          </div>
        </div>
      </div>
    </div>
  </div>
</template>
<script>
import { Button, FormGroupInput } from "@/components";
export default {
  name: "English",
  bodyClass: "English-page",
  components: {
    [Button.name]: Button,
    [FormGroupInput.name]: FormGroupInput,
  },
  data() {
    return {
      form: {
        firstName: "",
        email: "",
        message: "",
      },
        typeValue: '',
        typeStatus: false,
        typeArray: ['with state of the art techniques and technologies in Peru, under an innovative, efficient and environmentally friendly approach. '],
        typingSpeed: 75,
        // erasingSpeed: 100,
        // newTextDelay: 2000,
        typeArrayIndex: 0,
        charIndex: 0
      }
    },
    methods: {
      typeText() {
        if(this.charIndex < this.typeArray[this.typeArrayIndex].length) {
          if(!this.typeStatus)
            this.typeStatus = true;
          this.typeValue += this.typeArray[this.typeArrayIndex].charAt(this.charIndex);
          this.charIndex += 1;
          setTimeout(this.typeText, this.typingSpeed);
        }
        else {
          this.typeStatus = false;
          setTimeout(this.eraseText, this.newTextDelay);
        }
      },
      // eraseText() {
      //   if(this.charIndex > 0) {
      //     if(!this.typeStatus)
      //       this.typeStatus = true;
      //     this.typeValue = this.typeArray[this.typeArrayIndex].substring(0, this.charIndex - 1);
      //     this.charIndex -= 1;
      //     setTimeout(this.eraseText, this.erasingSpeed);
      //   }
      //   else {
      //     this.typeStatus = false;
      //     this.typeArrayIndex += 1;
      //     if(this.typeArrayIndex >= this.typeArray.length)
      //       this.typeArrayIndex = 0;
      //     setTimeout(this.typeText, this.typingSpeed + 1000);
      //   }
      // }
    },
    created() {
      setTimeout(this.typeText, this.newTextDelay + 200);
    }
  }
</script>
<style></style>
