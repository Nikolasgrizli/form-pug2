<template lang="pug">
.test
  h1 Test

  #app
    v-form(@submit='onSubmit')
      v-field(name='name' type='text' placeholder='Who are you' :rules='isRequired')
      error-message(name='name')
      button Submit
</template>

<style lang="scss">
@import "./../assets/scss/index.scss";

</style>
