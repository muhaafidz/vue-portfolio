<template>
  <div class="home">
    <h1>This is Home {{ name }}</h1>
    <ul>
      <li v-for="item in arr" :key="item.title">
        {{ item.title }}<br>
        {{ item.description }}
      </li>
    </ul>
  </div>
</template>

<script>
// @ is an alias to /src

export default {
  name: 'Home',
  components: {
  },
  data () {
    return {
      name: 'hahaha',
      arr: [
        {
          title: 'jojojo',
          description: 'jajaja'
        },
        {
          title: 'rororo',
          description: 'rururu'
        }
      ]
    }
  },
}
</script>
