<template>
  <div class="block-content-header sticky top-100">
    <ul class="float-right nav-bar flex w-10/12 mt-8 py-5 gap-5 overflow-hidden">
      <li class="text-white flex flex-col justify-center pl-5">
        <a href="/" class="text-center"> <img class="h-auto mx-auto" src="~assets/radio_blanc.svg">Radios</a>
      </li>
      <li class="text-white flex flex-col justify-center">
        <a href="podcasts" class="text-center"> <img class="h-auto mx-auto" src="~assets/podcast_blanc.svg">Podcasts</a>
      </li>
      <li class="text-white flex flex-col justify-center">
        <a href="blindtest" class="text-center"> <img class="h-auto mx-auto" src="~assets/jeux_blanc.svg">Blindtest</a>
      </li>
      <li class="text-white flex flex-col justify-center">
        <a href="vote" class="text-center"> <img class="h-auto mx-auto" src="~assets/vote_blanc.svg">Votes</a>
      </li>
      <li class="text-white flex flex-col justify-center">
        <a href="reecouter" class="text-center"> <img class="h-auto mx-auto" src="~assets/reecouter_blanc.svg">Réécouter</a>
      </li>
    </ul>
  </div>
</template>
<script>

export default {
  name: 'NavBar'
}
</script>
<style>
.nav-bar li{
  width: 29% !important;
}
.nav-bar{
  border-top-left-radius: 30px;
  border-bottom-left-radius: 30px;
  background-color: #D4000D;
box-shadow: 0px 3px 6px #00000029;

}
.block-content-header{
  height: 150px;
  width: 100%;
}
</style>
