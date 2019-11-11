<script>
export default {
  onLaunch: async function() {
    console.log("App Launch");
    // 测试直接跳转
    // await uni.reLaunch({
    //   url: "/pages/login/login"
	// });
	// 检测用户登录状态,如果登录这边会员
  },
  onShow: function() {
    console.log("App Show");
  },
  onHide: function() {
    console.log("App Hide");
  }
};
</script>
<style>
</style>
