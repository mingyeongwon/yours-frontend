<template>
  <div>
    <!-- 헤더 영역 -->
    <HeaderTabs/>

    <!-- 카드 영역 -->
    <div>
      <CardList/>
    </div>
  </div>
</template>

<script setup>
import { ref } from 'vue';
import HeaderTabs from '../components/HeaderTabs.vue';
import CardList from '../components/CardList.vue'


const allCards = ref([
  {
    imageSrc:
      "https://yt3.googleusercontent.com/CAHrv1abdyWrYZQpNwwjpeyPd-NcdGHU0jiPV_OO_V2uDG01P-GbfIUQA7bMpkTN08CxRZUu7w=s900-c-k-c0x00ffffff-no-rj",
    title: "나비야사랑해",
  },
  {
    imageSrc:
      "https://pbs.twimg.com/profile_images/991667101357129729/PUl9oyq-_400x400.jpg",
    title: "행동하는 동물사랑",
  },
  {
    imageSrc:
      "https://yt3.googleusercontent.com/-hFZuaymVFTBXQ6T7bCez93onedLqLrSPmCzE2oUKrNZW5knd-xyEZSlUZ45XfAj7RoPcy11Og=s900-c-k-c0x00ffffff-no-rj",
    title: "동물행동권 카라",
  },
  {
    imageSrc:
      "https://yt3.googleusercontent.com/CAHrv1abdyWrYZQpNwwjpeyPd-NcdGHU0jiPV_OO_V2uDG01P-GbfIUQA7bMpkTN08CxRZUu7w=s900-c-k-c0x00ffffff-no-rj",
    title: "나비야사랑해",
  },
  {
    imageSrc:
      "https://pbs.twimg.com/profile_images/991667101357129729/PUl9oyq-_400x400.jpg",
    title: "행동하는 동물사랑",
  },
  {
    imageSrc:
      "https://yt3.googleusercontent.com/-hFZuaymVFTBXQ6T7bCez93onedLqLrSPmCzE2oUKrNZW5knd-xyEZSlUZ45XfAj7RoPcy11Og=s900-c-k-c0x00ffffff-no-rj",
    title: "동물행동권 카라",
  },
  {
    imageSrc:
      "https://yt3.googleusercontent.com/CAHrv1abdyWrYZQpNwwjpeyPd-NcdGHU0jiPV_OO_V2uDG01P-GbfIUQA7bMpkTN08CxRZUu7w=s900-c-k-c0x00ffffff-no-rj",
    title: "나비야사랑해",
  },
  {
    imageSrc:
      "https://pbs.twimg.com/profile_images/991667101357129729/PUl9oyq-_400x400.jpg",
    title: "행동하는 동물사랑",
  },
  {
    imageSrc:
      "https://yt3.googleusercontent.com/-hFZuaymVFTBXQ6T7bCez93onedLqLrSPmCzE2oUKrNZW5knd-xyEZSlUZ45XfAj7RoPcy11Og=s900-c-k-c0x00ffffff-no-rj",
    title: "동물행동권 카라",
  },
]);
</script>

<style scoped></style>
