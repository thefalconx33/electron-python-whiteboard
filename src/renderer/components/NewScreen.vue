<template>
    <div>
        <el-button><a href="http://localhost:9080/#/"><i class="fas fa-home"></i></a></el-button>  
        <NavBar />
        <NewCanvas />
    </div>
</template>

<script>
import NavBar from './NavBar'
import NewCanvas from './NewCanvas'

export default {
  name: 'new-screen',
  components: { NavBar, NewCanvas }
}
</script>

<style scoped>
div{
    height: 100vh;
    overflow: hidden !important;
}

a {
    text-decoration: none;
    color: #000;
}
.el-button {
    position: absolute;
    z-index: 10;
    background-color: #ccc;
    border: none;
    color: #242424 !important;
}

.fa-home{
    font-size: 20px;
}

.fa-home:hover{
    color: white;
}
</style>

