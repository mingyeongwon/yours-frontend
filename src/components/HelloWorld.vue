<template>
  <div>
    <!-- 헤더 영역 -->
    <div>
      <h5 class="fw-bold">유어스</h5>
    </div>

    <!-- 탭 메뉴 영역 -->
    <div class="d-flex justify-content-between align-items-center">
      <div class="d-flex">
        <div class="me-3">전체</div>
        <div class="me-3">고양이</div>
        <div>강아지</div>
      </div>
      <div>문의하기</div>
    </div>

    <!-- 카드 영역 -->
    <!-- 'gy-4' 클래스로 수직 간격을 추가합니다 -->
    <div class="row mt-4 gy-4">
      <!-- 카드 1 -->
      <div class="col-md-3" v-for="allCard in allCards" :key="allCard.title">
        <div class="card rounded-2">
          <img
            :src="allCard.imageSrc"
            class="card-img-top rounded-2"
            :alt="allCard.title"
          />
          <div class="card-body">
            <p class="card-text">{{ allCard.title }}</p>
          </div>
        </div>
      </div>
    </div>
  </div>
</template>

<script setup>
import { ref } from "vue";

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
