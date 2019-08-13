<template>
    <div id="header">
        <h1>I'M JJang!</h1>
        <div class="menubar">
            <ul>
                <li><router-link to="/about" class="menu">About</router-link></li>
                <li><router-link to="/" class="menu">Home</router-link></li>
            </ul>
        </div>
    </div>
</template>

<script>
export default {
  name: 'Header',
  props: {

  }
}
</script>


<style>
#header {
    height: 500px;
    width: 100%;
    padding: 30px;
    background-image: url('../assets/오구1.jpg')
    /* background-color: gray; */
    /* justify-content: space-between; */
    /* align-content: space-between; */
}

#header a {
  font-weight: bold;
  color: #2c3e50;
}

#header h1 {
    display: inline-block;
    justify-content: center;
    vertical-align: middle;
}

#header a.router-link-exact-active {
  /* color: #42b983; */
}

.logo {
    float: right;
    margin-bottom: 2px;
}

li {
    display: inline;
    float: right;
}

.menubar {
    padding: 10px;
}

.menu {
    display: block;
    padding: 10px;
    background-color: blanchedalmond;
    text-decoration: none;
}


</style>
