<template>
    <v-footer dark padless>
      <v-card flat tile class="secondary white--text text-center">
        <v-card-text>
          <v-btn
            v-for="(icon, i) in icons"
            :key="i"
            class="mx-4 white--text"
            :href="icon.link"
            target="_blank"
            icon
          >
            <v-icon size="24px">{{ icon.text }}</v-icon>
          </v-btn>
        </v-card-text>
  
        <v-card-text class="white--text pt-0">
          How long are you going to wait before you demand the best for yourself?
        </v-card-text>
  
        <v-divider></v-divider>
  
        <v-card-text class="white--text">
          {{ new Date().getFullYear() }} — <strong>PT Pucink Max
  
          </strong>
        </v-card-text>
      </v-card>
    </v-footer>
  </template>
  
  <style scoped>
  .v-card {
    width: 100%;
  }
  </style>
  
  <script>
  export default {
    data: () => ({
      icons: [
        {
          text: "mdi-whatsapp",
          link: "http://wa.me/6281548191447",
        },
        {
          text: "mdi-instagram",
          link: "https://www.instagram.com/healthyfood_bymamamika?igsh=d2Y3eHZjcmUzeWoy",
        },
      ],
    }),
  };
  </script>