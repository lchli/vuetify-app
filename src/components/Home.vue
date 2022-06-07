<template>
  <v-container class="fill-height">

    <v-row :no-gutters="true" align="space-between" justify="space-between">
      <v-col cols="6" class="col-left">
        <v-card
            class="mx-auto"
            outlined
            height="100px"
        >
          <div class="item">
            胆码
          </div>
        </v-card>
      </v-col>


      <v-col cols="6" class="col-right">
        <v-card
            class="mx-auto"
            outlined
            height="100px"
        >
          <div class="item">
            杀码
          </div>
        </v-card>
      </v-col>


      <v-col cols="12" style="height: 10px"></v-col>

      <v-col cols="6" class="col-left">
        <v-card
            class="mx-auto"
            outlined
            height="100px"
        >
          <div class="item">
            胆码
          </div>
        </v-card>
      </v-col>


      <v-col cols="6" class="col-right">
        <v-card
            class="mx-auto"
            outlined
            height="100px"
        >
          <div class="item">
            杀码
          </div>
        </v-card>
      </v-col>

    </v-row>

  </v-container>
</template>

<script>

export default {
  name: 'HomePage',

  data: () => ({
    ecosystem: [
      {
        text: 'vuetify-loader',
        href: 'https://github.com/vuetifyjs/vuetify-loader',
      },
      {
        text: 'github',
        href: 'https://github.com/vuetifyjs/vuetify',
      },
      {
        text: 'awesome-vuetify',
        href: 'https://github.com/vuetifyjs/awesome-vuetify',
      },
    ],
    importantLinks: [
      {
        text: 'Chat',
        href: 'https://community.vuetifyjs.com',
      },
      {
        text: 'Made with Vuetify',
        href: 'https://madewithvuejs.com/vuetify',
      },
      {
        text: 'Twitter',
        href: 'https://twitter.com/vuetifyjs',
      },
      {
        text: 'Articles',
        href: 'https://medium.com/vuetify',
      },
    ],
    whatsNext: [
      {
        text: 'Explore components',
        href: 'https://vuetifyjs.com',
      },
      {
        text: 'Roadmap',
        href: 'https://vuetifyjs.com/introduction/roadmap/',
      },
      {
        text: 'Frequently Asked Questions',
        href: 'https://vuetifyjs.com/getting-started/frequently-asked-questions',
      },
    ],
  }),
}
</script>

<style lang="scss" scoped>
.item {
  display: flex;
  align-items: center;
  justify-content: center;
  height: 100%;
}

.col-left {
  padding-right: 5px !important;
}

.col-right {
  padding-left: 5px !important;
}

</style>
