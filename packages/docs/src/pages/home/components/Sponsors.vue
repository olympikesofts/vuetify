<template>
  <v-card flat color="grey lighten-4 pa-5 text-xs-center">
    <v-subtitle-1 class="title font-weight-regular">
      Patreon Sponsors
    </v-subtitle-1>

    <supporters-patrons
      :tier="3"
      class="mb-5"
      dense
      hide-titles
    />

    <v-subtitle-1 class="title font-weight-regular mb-5">
      Open Collective Sponsors
    </v-subtitle-1>

    <supporters-sponsor-btn
      append
      to="getting-started/sponsors-and-backers"
      large
    />
  </v-card>
</template>
