<template>
  <div>
    <v-toolbar light>
      <v-toolbar-side-icon light></v-toolbar-side-icon>
      <v-toolbar-title>Toolbar</v-toolbar-title>
      <v-spacer></v-spacer>
      <v-btn icon light>
        <v-icon>account_circle</v-icon>
      </v-btn>
    </v-toolbar>
    <v-container>
      <v-card>
        <v-card-text>
          <nuxt/>
        </v-card-text>
      </v-card>
    </v-container>
  </div>
</template>
