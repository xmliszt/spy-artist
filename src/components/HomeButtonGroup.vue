<template>
  <div class="home-button-group">
    <h1 class="title">Spy-Artist</h1>
    <el-card shadow="hover">
      <div class="btn-row">
        <el-button class="menu-btn" type="primary">Create New Room</el-button>
      </div>
      <div class="btn-row">
        <el-button class="menu-btn" type="warning">Join A Room</el-button>
      </div>
      <div class="btn-row">
        <el-button class="menu-btn" type="info">Help</el-button>
      </div>
    </el-card>
  </div>
</template>

<script>
export default {};
</script>

<style>
.title {
  font-size: 80px;
  font-weight: 700;
  font-variant: small-caps;
  font-family: "Gill Sans", "Gill Sans MT", Calibri, "Trebuchet MS", sans-serif;
  margin-bottom: 30px;
}

.home-button-group {
  text-align: center;
}

.btn-row {
  margin-bottom: 20px;
  margin-top: 20px;
}

.menu-btn {
  font-variant: small-caps;
  font-size: 40px;
  font-weight: 700;
  width: 500px;
  height: 100px;
}

.el-card {
  width: 600px;
  display: inline-block;
}
</style>
