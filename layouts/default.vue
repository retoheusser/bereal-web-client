<template>
 <v-app>
  <v-app-bar app>
    <v-app-bar-title class="d-flex justify-center">
      <span class="font-weight-bold">BeFake.</span>
    </v-app-bar-title>
  </v-app-bar>

  <!-- Sizes your content based upon application components -->
  <v-main>

    <!-- Provides the application the proper gutter -->
    <v-container fluid>

      <!-- If using vue-router -->
      <slot />
    </v-container>
  </v-main>

  <v-footer class="d-flex justify-center" app>
    retoz 💪🏽 2023
  </v-footer>
</v-app>
</template>