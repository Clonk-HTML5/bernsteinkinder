<template>
  <div>

    <b-card
      overlay
      img-src="https://source.unsplash.com/ux53SGpRAHU/1600x900"
      img-alt="Card Image"
      body-class="text-center"
      align="center"
      text-variant="white"
      title="Bernsteinkinder"
      sub-title="Hebammenpraxis"
    >
      <b-card-text>
        befindet sich noch im Aufbau!
      </b-card-text>
    </b-card>
    <b-container>
        <b-row>
          <b-col l="4">
          <b-card
            title="Antje Dembek"
            img-src="https://picsum.photos/600/300/?image=25"
            img-alt="Image"
            img-top
            tag="article"
            style="max-width: 20rem;"
            class="mb-2"
          >
            <b-card-text>
              zu Erreichen unter der Nummer 017684097248
            </b-card-text>

<!--            <b-button href="#" variant="primary">zur Webseite</b-button>-->
          </b-card>
          </b-col>
          <b-col l="4">
          <b-card
            title="Erika Lemke"
            img-src="https://picsum.photos/600/300/?image=25"
            img-alt="Image"
            img-top
            tag="article"
            style="max-width: 20rem;"
            class="mb-2"
          >
            <b-card-text>
              zu Erreichen unter der Nummer 015121661477
            </b-card-text>

            <b-button href="https://www.hebammeerikalemke.de" target="_blank" variant="primary">zur Webseite</b-button>
          </b-card>
          </b-col>
        </b-row>
      </b-container>
  </div>
</template>

<script>
import Logo from '~/components/Logo.vue'

export default {
  components: {
    Logo
  }
}
</script>

<style>
.container {
  margin: 0 auto;
  min-height: 100vh;
  display: flex;
  justify-content: center;
  align-items: center;
  text-align: center;
}

.title {
  font-family: 'Quicksand', 'Source Sans Pro', -apple-system, BlinkMacSystemFont,
    'Segoe UI', Roboto, 'Helvetica Neue', Arial, sans-serif;
  display: block;
  font-weight: 300;
  font-size: 100px;
  color: #35495e;
  letter-spacing: 1px;
}

.subtitle {
  font-weight: 300;
  font-size: 42px;
  color: #526488;
  word-spacing: 5px;
  padding-bottom: 15px;
}

.links {
  padding-top: 15px;
}
</style>
