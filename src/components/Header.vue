<template>
   <header>
    <div class="logo">
      <img src="/public/author-logo-round.png" alt="Logo Author">
    </div>
    <nav class="main-menu">
      <ul>
        <li
          v-for="(item,index) in mainMenu"
          :key="index"
        ><a :href="item.href">{{ item.text }}</a></li>
      </ul>
    </nav>
  </header>
</template>

<script>
import mainMenu from '../data/mainMenu'

export default {
  name: 'Header',
  data(){
    return{
      mainMenu
    }
  }
}
</script>

<style scoped>
@use 'src/components/scss/_variabiles.scss as *;

header{
  text-align: center;
  margin-bottom: 50px;
  .logo{
    margin-bottom: 50px;
  }
  ul{
    li{
      display: inline-block;

      a{
        color: $link-color;
        text-transform: capitalize;
        font-weight: bold;
        padding: 15px;
        &:hover{
          background-color: lighten($primary-color, 65%);
        }
      }
    }
  }
}
</style>
