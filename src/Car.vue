<template>
    <div>
        <h3> {{ carName }}</h3>
        <p>{{ carYear }}</p>
    </div>
</template>

<script>
export default {
  data () {
    return {
      carName: 'Tesla',
      carYear: 2015
    }
  }
}
</script>
