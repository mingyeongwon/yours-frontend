<template>
  <div>
    <!-- 헤더 영역 -->
    <div>
      <h5 class="fw-bold">유어스</h5>
    </div>

    <!-- 탭 메뉴 영역 -->
    <div class="d-flex justify-content-between align-items-center my-3">
      <!-- 왼쪽 탭 메뉴 (전체, 강아지, 고양이) -->
      <div class="d-flex">
        <div
          v-for="(tab, index) in leftTabs"
          :key="index"
          class="me-3 cursor-pointer"
        >
          {{ tab }}
        </div>
      </div>
      <!-- 오른쪽 탭: 문의하기 -->
      <div class="cursor-pointer">문의하기</div>
    </div>
  </div>
</template>

<script>
impo
</script>

<style scoped></style>