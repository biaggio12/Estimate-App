<template>
  <nav>
    <ul id="nav">
      <li v-for="item in navItems"><a href="#">{{item}}</a></li>
    </ul>
  </nav>
</template>

<script>
export default {
  name: 'NavBar',
  data: function(){
    return {
        navItems: ['Sklep Internetowy','Strona Internetowa','Aplikacja internetowa','Blog','One Page'],
            }
                  },
  methods: {
    },
  }

</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped lang="scss">
#nav {
  list-style:none;
  display:flex;
  flex-direction:row;
  justify-content:flex-start;
  background:#333333;
  margin:5px 12px;
  padding:0px;
}
#nav li a {
  display:block;
  padding:10px 22px;
  color:#ffffff;
  text-decoration:none;
}
#nav li a:hover {
  background-color: #111111;
}
.active {
  background-color: #4CAF50;
}
</style>
