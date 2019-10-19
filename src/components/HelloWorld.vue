<template>
  <div class="hello">
    <div class="parent">
      <div class="item item-1">这是1</div>
      <div class="item item-2">这是2</div>
      <div class="item item-3">这是3</div>
      <div class="item item-4">这是4</div>
      <div class="item item-5">这是5</div>
      <div class="item item-6">这是6</div>
      <div class="item item-7">这是7</div>
      <div class="item item-8">这是8</div>
      <div class="item item-9">这是9</div>
      <div class="item item-0">这是10</div>
    </div>
  </div>
</template>

<script>
export default {
  name: 'HelloWorld',
  props: {
    msg: String
  }
}
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped>
.parent{
 display: grid;
 grid-row-gap: 20px;
  grid-column-gap: 40px;
  /* grid-template-columns:repeat(auto-fit, 200px); */
  /* grid-template-columns: 1fr 1fr minmax(400px, auto); */
  grid-template-columns: repeat(auto-fill, minmax(400px,1fr));
  /* grid-template-rows: repeat(3, 200px); */
}
.item {
  font-size: 2em;
  text-align: center;
  border: 1px solid #e5e4e9;
  height: 300px;
}

.item-1 {
  background-color: #ef342a;
}

.item-2 {
  background-color: #f68f26;
}

.item-3 {
  background-color: #4ba946;
}

.item-4 {
  background-color: #0376c2;
}

.item-5 {
  background-color: #c077af;
}

.item-6 {
  background-color: #f8d29d;
}

.item-7 {
  background-color: #b5a87f;
}

.item-8 {
  background-color: #d0e4a9;
}

.item-9 {
  background-color: #4dc7ec;
}
</style>
