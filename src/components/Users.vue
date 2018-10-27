<template>
    <div id="users">
      <h1>users</h1>
      <ul>
        <li v-for="user in users">
          {{user}}
        </li>
      </ul>
    </div>
</template>

<script>
    export default {
        name: "Users",
      data(){
          return {
            users: ['Herry', 'Bucky', 'Yoshi']
          }
      }
    }
</script>

<style scoped> /* coped 限定以下定义的样式仅在当前组件里起作用*/
h1 {
  color: green;
}
</style>
