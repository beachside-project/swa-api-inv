<template>
  <div>
    Hello B2C {{ value }}
    <div>
      <a href="/.auth/login/b2c">Login</a>
    </div>
    <div>
      <a href="/me">My Info</a>
    </div>
    <div>
      <a href="/api/func/Function1">Call API on Function App via proxy</a>
    </div>
    <div>
      <a href="/api/web/swa">Call API on Web App via proxy</a>
    </div>
    <div>
      <a href="/direct">Call API on Web App direct</a>
    </div>
    <div>
      <a href="/direct401">Call 401 API </a>
    </div>
    <div>
      <a href="/direct403">Call 403 API </a>
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
