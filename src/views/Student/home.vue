<template>
  <div>
    <el-container>
      <el-main>
        <h1>student home</h1>
        <info-card></info-card>
        <el-card style="width: 100%; margin-top: 10px">
          <p><i class="el-icon-s-home" style="margin-right: 18px"></i>教学管理平台管理系统</p>
          <p><i class="el-icon-s-custom" style="margin-right: 18px"></i>作者：本人</p>
          <p><i class="el-icon-chat-round" style="margin-right: 18px"></i>后端：SpringBoot，前端：Vue</p>
        </el-card>
        <logout></logout>
      </el-main>
    </el-container>
  </div>
</template>

<script>
import Logout from "@/components/logout";
import InfoCard from "@/components/infoCard";
export default {
  name: "home",
  components: {InfoCard, Logout},
}
</script>

<style scoped>

</style>
