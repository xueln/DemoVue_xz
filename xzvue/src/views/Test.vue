<template>
  
  <div>
    <div>{{new Date()}}</div>
    <div>{{JSON.stringify(user)}}</div>
  </div>
</template>

<script>
export default {
  data(){
    return {
      user:{ name:"ding"}
    }
  }
}

</script>
