<template>
  <div>
    <h1>Show del post</h1>
    <p>
        Lo slug del posts è : {{ slug }}
    </p>
  </div>
</template>

<script>
export default {
   props: [
      'slug',
   ]
}
</script>

<style>

</style>
