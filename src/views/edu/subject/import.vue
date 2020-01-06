<template>

</template>

<script>
  export default {
    name: 'import',
    data() {
      return {
        BASE_API: process.env.BASE_API, // 接口API地址
        OSS_PATH: process.env.OSS_PATH, // 阿里云OSS地址
        fileUploadBtnText: '上传到服务器', // 按钮文字
        importBtnDisabled: false, // 按钮是否禁用,
        loading: false
      }
    }
  }
</script>

<style scoped>

</style>
