<script setup>

</script>

<template>
  <section class="container-fluid">
    <div class="row justify-content-center pt-3">
      <div class="col-3 header-box text-center fst-italic">
        <h1>Kate's Lashes</h1>
      </div>
    </div>
    <div class="row justify-content-center pt-3">
      <div class="col-4 d-flex justify-content-center">
        <button class="header-btn">Home</button>
        <button class="header-btn ms-3 me-3">Styles</button>
        <button class="header-btn">Schedule</button>
      </div>
    </div>
  </section>
</template>

<style scoped lang="scss">
.header-box{
  font-family: 'Franklin Gothic Medium', 'Arial Narrow', Arial, sans-serif;
  border-bottom: solid 1px black;
}

.header-btn{
  all: unset;
  padding-top: 4px;
  padding-bottom: 4px;
  padding-left: 5px;
  padding-right: 5px;
  color: white;
  background-color: rgb(184, 114, 126);
  outline: solid 2px rgb(160, 96, 107);
  border-radius: 6px;
}

.header-btn:hover{
  all: unset;
  padding-top: 4px;
  padding-bottom: 4px;
  padding-left: 5px;
  padding-right: 5px;
  color: white;
  background-color: rgb(199, 123, 136);
  outline: solid 2px rgb(160, 96, 107);
  border-radius: 6px;
  cursor: pointer;
}
</style>
