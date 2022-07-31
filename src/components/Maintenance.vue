<template>
  <div class="maintenance">
    <img alt="Vue logo" src="../assets/hammer-and-wrench-microsoft.png" />
    <h1>Under Maintenance</h1>
    <p class="message">
      We are very sorry we're unable to process all of your requests right now.
      We are having our server maintenance and will get back to you as soon as
      possible.
    </p>
    <a href="https://www.facebook.com/teamhrlgubayawan" class="footer"
      >#TEAMHR</a
    >
  </div>
</template>

<script>
export default {
  name: "Maintenance",
};
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped>
.message {
  font-size: 32px;
}
.footer {
  font-size: 28px;
}
h3 {
  margin: 40px 0 0;
}
ul {
  list-style-type: none;
  padding: 0;
}
li {
  display: inline-block;
  margin: 0 10px;
}
a {
  color: #42b983;
}
</style>
