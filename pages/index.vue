<template>
  <div>
    <DruxtView :view-id="user_admin_people" />
   test </div>
</template>

<script>
const { DruxtClient } = require('druxt')
const druxt = new DruxtClient('https://dev-markoul.pantheonsite.io')
export default {
  name: 'IndexPage'
}
</script>
