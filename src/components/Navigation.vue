<template>
  <div id="navigation" style="display: block;">
    <ul style="float: left;">
      <li>Home</li>
      <li>Books</li>
      <li>About</li>
    </ul>
    <div class="search" style="float: right;">
      <input
        type="text"
        placeholder="Search for Books, and more."
      />
      <i class="fas fa-search"></i>
    </div>
  </div>
</template>

<script lang="ts">
export default {};
</script>

<style scoped>
#navigation {
  display: flex;
  width: 100%;
  margin-bottom: 50px;
}
#navigation ul {
  display: flex;
  list-style: none;
  padding: 10;
  margin: 0 20px 0 0;
}
#navigation ul li {
  font-size: 2rem;
  padding: 2px 10px;
  cursor: pointer;
}
#navigation ul li:hover {
  color: #a97171;
}
#navigation .search {
  position: relative;
  width: 100%;
  max-width: 500px;
}
#navigation .search input {
  border: none;
  outline: none;
  width: calc(100% - 140px);
  padding: 15px 60px 15px 20px;
  margin: 0;
  border-radius: 30px;
  background-color: #efefef;
  /* font-family: "Segoe UI", Tahoma; */
  font-family:courier,arial,helvetica;
  font-size: 1rem;
}
#navigation .search i {
  position: absolute;
  right: 80px;
  top: 15px;
  font-size: 1.2rem;
  color: #aaa;
  cursor: pointer;
}
</style>