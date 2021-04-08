<template>
    <div>
        <h4>Messages</h4>
        <v-list>
      
        <v-list-item v-for="message in messages" @click="">
            
            <v-list-item-content>
                <v-list-item-title v-text="message"></v-list-item-title>
            </v-list-item-content>

      </v-list-item>
    </v-list>

     </div>   
</template>

<script>
export default {
   data: function() {
       return{
           messages: ["Hello", "Hi", "Hey there"]
       }
   }
}
</script> 