<template>
  <v-container class="fill-height center">

    <v-row no-gutters="true" align="center" justify="center">
      <v-col cols="12">
        <v-text-field
            dense
            label="用户名"
            placeholder="输入用户名"
            rounded

        ></v-text-field>
      </v-col>

      <v-col cols="12">
        <v-text-field
            label="密码"
            placeholder="输入密码"
            rounded
            dense
        ></v-text-field>
      </v-col>
      <v-col class="center">
        <v-btn
            width="100%"
            height="50px"
            color="primary"
        >登录
        </v-btn>
      </v-col>


    </v-row>

  </v-container>
</template>

<script>

export default {
  name: 'HelloWorld',

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

<style lang="scss">
.center{
  display: flex;
  align-items: center;
  justify-content: center
}

</style>
