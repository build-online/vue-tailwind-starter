<template>
  <div id="app" class="max-w-xl mx-auto font-sans leading-normal">
    <img src="./assets/tailwind.jpg" class="block mx-auto">
    {{#router}}
    <router-view/>
    {{else}}
    <HelloWorld/>
    {{/router}}
  </div>
</template>

<script>
{{#unless router}}
import HelloWorld from './components/HelloWorld'

{{/unless}}
export default {
  name: 'App'{{#router}}{{else}},
  components: {
    HelloWorld
  }{{/router}}
}
</script>

<style>
</style>
<style src="./styles/main.css"></style>