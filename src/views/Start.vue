<template>
  <v-container fill-height>
    <v-row justify="center" align="center">
      <v-col cols="6">
        <h1>Drinccup</h1>
        <p>The drinking game to play with your friends, or foes...</p>
        <p>You will be put in a 'room' with up to 20 players, that's when the fun will start.</p>
        <p><small>Please drink responsibly ;)</small></p>
        <v-card elevation="2">
          <v-card-title>Create a game</v-card-title>
          <v-card-subtitle>All you need to do is come up with a name for your room, click this button, then we'll do the rest!</v-card-subtitle>
          <v-text-field label="Room Name" v-model="roomName" class="mx-4"></v-text-field>
          <v-card-actions>
            <v-btn depressed color="primary">Go!</v-btn>
          </v-card-actions>
        </v-card>
      </v-col>
    </v-row>



  </v-container>
</template>

<script lang="ts">
import { Component, Vue } from 'vue-property-decorator';

@Component({
  components: {
    
  },
})
export default class Start extends Vue {
  roomName = 'Test'
}
</script>
