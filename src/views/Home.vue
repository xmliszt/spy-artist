<template>
  <div class="home">
    <HomeButtonGroup />
    <AnimatedBG />
  </div>
</template>

<script>
import HomeButtonGroup from "@/components/HomeButtonGroup";
import AnimatedBG from "@/components/AnimatedBG";
export default {
  name: "Home",
  components: {
    AnimatedBG,
    HomeButtonGroup
  }
};
</script>
