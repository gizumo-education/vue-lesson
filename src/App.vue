<template>
  <div>
    <h1>Hello Vue!</h1>
  </div>
</template>

<script>
export default {

};
</script>

<style lang="scss">
.main {
  height: 100vh;
  background-color: rgb(250, 250, 250);
}

.section {
  width: 60%;
  margin: 0 auto;
  background-color: #fff;
  padding: 16px;
  border-radius: 4px;
  margin-bottom: 20px;
  box-shadow: 0 3px 1px -2px rgb(0 0 0 / 20%), 0 2px 2px 0 rgb(0 0 0 / 14%), 0 1px 5px 0 rgb(0 0 0 / 12%);
  &_name {
    color: #03a9f4;
    margin: 0;
  }
}

.divider {
  height: 2px;
  background-color: #03a9f4;
}

.green {
  color: green;
}
</style>
