<template>
  <div class="about">
    <h1>Hello {{ their_name }}, this is a page about me</h1>
    <p>I am a fresh Junior Web developer able to build a Web presence from the ground up -- from concept, navigation, layout and programming to UX and SEO.
I think that the full-stack development skills I've gained in my recent schooling, and my background in Digital Marketing, would make me a great fit for any company. 
On top of that, I am the fun, enjoyable presence that every office needs.
</p>
  </div>
</template>


<script>
export default {
  name: 'Skills',
  data() {
    return {
      their_name: this.$route.params.name
    }
  }
}
</script>
