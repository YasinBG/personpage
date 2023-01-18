<template>
  <div class="bg-green-400">
    
    <CardText>
        <template #title>How are we going to make it?</template>
    </CardText>

    <CardText>
      <template #content> Lorem ipsum dolor sit amet consectetur adipisicing elit. Totam dolorem optio omnis, hic ut consequuntur odit suscipit tempore reiciendis soluta quis sint dolore aliquid aperiam ullam eius harum. Voluptatibus, excepturi? </template>
    </CardText>

  </div>

  <Button>
    <template #button>BUTTON</template>
  </Button>
</template>

<script>
import Button from './components/Button.vue'
import CardText from './Layout/CardText.vue'


export default {
  name:"App",
  components:{
    CardText,
    Button
  },

}
</script>

<style>

</style>