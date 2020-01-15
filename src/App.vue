<template>
<div>
    <app-navbar />
      <p>Lorem ipsum dolor sit, amet consectetur adipisicing elit. Iure fugiat officia error perferendis voluptates doloremque. Maiores reprehenderit numquam, delectus corrupti animi minima enim cumque ipsam, pariatur exercitationem ratione id sint?
    </p>
    <app-footer />
</div>
</template>

<script>
import Navbar from "./components/Navbar";
import Footer from "./components/Footer";

export default {
  components: {
    "app-navbar": Navbar,
    "app-footer": Footer
  }

}
</script>

<style>

</style>