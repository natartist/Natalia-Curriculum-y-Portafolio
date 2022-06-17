<template>
<div class="container">
  <div class="row fila-5">
    <!-- <footer> -->
    <footer style="background-color: #fcfce2;">
    <!-- <div class="row fila-5" style="background-color: #fcfce2;"> -->
      <!-- formulario -->
      <form ref="form" @submit.prevent="sendEmail">
        <div class="caja7 col-md-6 col-xs-12">
          <div class="mb-3">
            <label for="user" class="form-label">Nombre</label>
            <input
              type="text"
              class="form-control"
              id="user"
              name="user_name"
            />
            <div id="nameHelpBlock" class="form-text">Escribe tu nombre.</div>
          </div>

          <div class="mb-3">
            <label for="mail" class="form-label">Email</label>
            <input
              type="email"
              class="form-control"
              id="mail"
              name="user_email"
            />
            <div id="nameHelpBlock" class="form-text">Escribe tu email.</div>
          </div>
        </div>

        <div class="caja8 col-md-6 col-xs-12">
          <div class="mb-3">
            <label for="mail" class="form-label">Comentarios</label>
            <div class="form-floating">
              <textarea
                name="message"
                class="form-control"
                style="height: 120px"
              ></textarea>
            </div>
          </div>
          <button type="submit" class="btn btn-light">Enviar</button>
        </div>
      </form>
      <!-- fin del formulario -->
    </footer>
  <!-- </footer> -->
    </div>
 </div>
</template>

<script>
import emailjs from "emailjs-com";

export default {
  name: "HomeView",

  components: {},
  methods: {
    sendEmail() {
      emailjs
        .sendForm(
          "service_id5i86r",
          "template_bxe159k",
          this.$refs.form,
          "GTXCMTTS14DOrzPT8"
        )
        .then(
          (results) => {
            console.log("success!", results.text);
          },
          (error) => {
            console.log("failed...", error.text);
          }
        );
    },
  }
}
</script>

<style>

</style>