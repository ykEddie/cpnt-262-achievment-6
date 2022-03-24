<template>
  <div class="inset-x-0 bottom-0">
    <nav role="navigation" class="inset-x-0 bottom-0">
      <ul class="absolute inset-x-0 bottom-0 text-sm">
        <li></li>
        <li><a href="#">Newsletter</a></li>
        <li><a href="#">Accessibility</a></li>
        <li><a href="#"></a></li>
        <li><a href="#"></a></li>
        <li><a href="#"></a></li>
        <li><a href="#">&copy; Ed Adeagbo 2022</a></li>
        <li><a href="#" class="text-right">CHAT</a></li>
        <li><a href="#">CONTACT</a></li>
        <li><a href="#">FEATURES</a></li>
        <li><a href="#">CHAPTERS</a></li>
      </ul>
    </nav>
  </div>
</template>

<style>
nav {
  background-color: white;
  font-size: 19px;
}

ul {
  list-style-type: none;
  display: flex;
  margin-right: 2rem;
  flex-wrap: wrap;
  flex-grow: 2;
  justify-content: space-between;
}

li > a:hover {
  color: green;
  text-decoration: underline;
}
li > a {
  text-decoration: none;
  color: black;
  font-family: "Roboto", sans-serif;
}

li > a:visited {
  text-decoration: black;
  color: black;
}
</style>
