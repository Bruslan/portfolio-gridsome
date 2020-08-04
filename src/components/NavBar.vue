<template>
  <nav class="side">
    <div class="side__inner border-r border-dashed border-gray-700">
      <div class="top">
        <a  class="hover:text-yellow-700" href="#">Bruslan</a>
      </div>
      <div class="bottom">
        <a class="mr-4 hover:text-yellow-700" target="_blank" href="https://www.facebook.com/bruslan">FACEBOOK</a>
        <a class="mr-4 hover:text-yellow-700" target="_blank"  href="https://www.linkedin.com/in/ruslan-noschajew-6228a3196/" >LINKED IN</a>
        <a class="mr-4 hover:text-yellow-700" target="_blank"  href="mailto:noschajew.ruslan@gmail.com">EMAIL ME</a>
      </div>
    </div>
  </nav>
</template>

<script>
export default {};
</script>

<style scoped>
.side {
  
  position: fixed;
  top: 0;
  left: 0;
  bottom: 0;
  z-index: 1000;
  width: 50px;
  /* border-right: 1px dashed rgba(black, 0.3); */
  color: rgba(black, 0.5);

  text-transform: uppercase;
  letter-spacing: 0.0875rem;
  font-size: 10px;
}

.side__inner {
  position: relative;
  height: 100%;
  white-space: nowrap;
}

.top {

  top: 0;
  text-align: right;
  color: black;
}

.bottom {
   
  top: auto;
  bottom: 200px;
}

a {
  color: inherit;
  word-spacing: 0;
}

.top,
.bottom {
  position: absolute;
  left: 0;
  transform: rotate(-90deg) perspective(1px);
  transform-origin: 50px 50px;
  height: 100px;
  line-height: 50px;
  white-space: nowrap;
  word-spacing: 0.5rem;
}
</style>