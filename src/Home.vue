<template>
    <div>
      Server Status is: {{status}}
      <hr>
      <button @click = "changeStatus">Change Status</button>

    </div>
</template>

<script>
    export default {
        name: "home",
        data: function () {
          return {
            status: "Normal"
          }
        },
          methods:{
            changeStatus(){
              this.status = "Critical"
            }
          }
    }
</script>

<style scoped>

</style>
