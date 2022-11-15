<template>
  <div class="text-info">
    <h1>حمل تطبيق مول لهري</h1>
    <p>
      مول لهري أول تطبيق فالمغرب تقدر تكوموندي لي بغيتي ومن تيليفونك، فيه جميع
      المواد الغذائية ومواد التنظيف، الحليب و الأجبان و غيرها من مستلزمات البيت
      ماعليك غير تحمل التطبيق وتسوق على خاطرك، يكفي تأكد الطلبية والتقدية ديالك
      توصلك تال باب دارك وفنص ساعة التوصيل غير ب5 دراهم
    </p>
    <div class="downloads">
      <div class="app-gp">
        <a
          href="https://play.google.com/store/apps/details?id=com.storeino.app.moulhri"
          target="_blank"
        >
          <img src="../assets/images/google-play.svg" alt="" />
        </a>
      </div>
      <div>
        <a
          href="https://apps.apple.com/ma/app/%D9%85%D9%88%D9%84-%D9%84%D9%87%D8%B1%D9%8A-moulhri/id1642047102?l=fr"
          target="_blank"
        >
          <img src="../assets/images/apple-store.svg" alt="" />
        </a>
      </div>
    </div>
  </div>
</template>

<script setup></script>

<style scoped>
.text-info {
  direction: rtl;
  font-family: Arial, Helvetica, sans-serif;
  text-align: center;
}

.text-info h1 {
  font-size: 2.8rem;
  font-weight: bold;
  text-align: center;
}

.text-info p {
  font-size: 1rem;
}

.downloads {
  text-align: center;
  display: flex;
  justify-content: center;
  gap: 15px;
  padding: 20px 0;
}

.downloads img {
  height: 40px;
  /* width: 90px; */
}

@media (min-width: 1080px) {
  .text-info {
    width: 550px;
    padding: 0 10px;
  }

  .text-info h1 {
    font-size: 3.2rem;
    font-weight: bold;
  }

  .downloads {
    align-items: center;
  }
  .downloads img {
    height: 40px;
  }
} 

</style>
