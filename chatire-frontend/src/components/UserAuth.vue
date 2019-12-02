<template>
  <div class="container">
<strong>This site is not active yet. It is being live coded.</strong>
<!--<iframe class="airtable-embed airtable-dynamic-height" src="https://airtable.com/embed/shr3emMgsXJ7jyZ0O?backgroundColor=orange" frameborder="0" onmousewheel="" width="100%" height="3072" style="background: transparent; border: 1px solid #ccc;"></iframe>
    -->
<h1 style="text-align:center">21st technology protecting life and property</h1>

<div v-if="screen == 'home'">

<button @click="screen = 'forCitizens'" type="button" class="btn btn-primary"  style="margin-bottom:4px;white-space: normal;width:100%;font-size:1.5em">For citizens: Report an emergency or non-emergency and get notifications</button>
<button @click="screen = 'forFirstResponders'" type="button" class="btn btn-primary"  style="margin-bottom:4px;white-space: normal;width:100%;font-size:1.5em">For official first responders and dispatchers: Receive emergency and non-reports and send notifications</button>
</div>
<div v-if="screen == 'forCitizens'">
<h2 style="text-align:center">For citizens</h2>
<button @click="screen = 'forCitizens'" type="button" class="btn btn-danger"  style="margin-bottom:4px;white-space: normal;width:100%;font-size:1.5em">Report an emergency: a situation that could, or does, pose a danger to life, property or both, suspicious activity involving a person(s) or vehicle that appears to have criminal intent, crime that just occurred and suspects are in the immediate area, person injured, serious crime such as robbery, domestic violence or sexual assault</button>
<button @click="screen = 'forCitizens'" type="button" class="btn btn-warning"  style="margin-bottom:4px;white-space: normal;width:100%;font-size:1.5em">Report a non-emergency</button>


</div>
    </div>
  
</template>

<script>
  const $ = window.jQuery // JQuery

  export default {

    data () {
      return {
        screen: 'home', email: '', username: '', password: ''
      }
    },

    methods: {
      forCitizens() {
        
      },

      forFirstResponders() {
        
      }
    }

  }
</script>

<style scoped>

</style>
