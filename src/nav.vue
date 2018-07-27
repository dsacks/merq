<template>
  <select >
    <option v-for="item in items" value="{{item.value}}">{{item.name}}</option>
  </select>
</template>

<script>
export default {
  name: 'item',
  data () {
    return {
       items: [
           { value: 'v1', name: 'volume1'},
           { value: 'v2', name: 'volume2'},
           { value: 'v3', name: 'volume3'},
           { value: 'v4', name: 'volume4'},
       ]
    }
  }
}
</script>

<style>
</style>