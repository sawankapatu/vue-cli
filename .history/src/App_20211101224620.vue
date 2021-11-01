<template>
  <div id="app">
    <div class="container">
      <h1 align="center">Workshop #1 | Limit Message</h1>
      <hr>
      <div class="input-group">
        <div class="input-group-prepend">
          <span class="input-group-text">20</span>
        </div>
        <input type="text" class="form-control" v-model="message"> <!-- ผูกกับ data message แล้ว ถ้าพิมอะไรไปก็จะไปเก็บไว้ในนั้น -->
      </div>
    </div>
  </div>
</template>

<script>
export default {
  name: 'App',
  data(){
    return{
      message:""
    }
  }
}
</script>