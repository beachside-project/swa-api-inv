<template>
  <div>
    Hello B2C {{ value }}
    <div>
      <a href="/.auth/login/b2c">Login</a>
    </div>
    <div>
      <a href="/.auth/me">My Info</a>
    </div>
    <div>
      <a href="/api/func/Function1">Call Function API via proxy</a>
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
