<template>
  <div>
    Hello {{ value }}
    <div>
      <a href="/.auth/login/b2c">Login</a>
    </div>
    <div>
      <a href="/.auth/me">My Info</a>
    </div>
  </div>
</template>

<script>
export default {
  name: "App",
  data() {
    return {
      value: "World",
    };
  },
};
</script>
