<template>
  <div class=test>
    <h1>{{test}}</h1>
    <p>This is a test components written by Eric</p>
  </div>
</template>

<script>
export default {
  name: 'test',
  data () {
    return {
      test: 'This is a test'
    }
  }
}
</script>
