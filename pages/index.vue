<template>
  <header class="flex justify-around items-center mt-4">
    <div>
      <h1>السير فى خطى الصحابة</h1>
      <h1 class="text-orange-500">رضي الله عنهم</h1>
    </div>
    <img src="@/assets/images/logo.png" alt="hayat al-sahaba" />
  </header>
</template>

<script>

export default {
 
}
</script>

<style lang="scss">
/* Sample `apply` at-rules with Tailwind CSS
.container {
  @apply min-h-screen flex justify-center items-center text-center mx-auto;
}
*/

header { 
  h1 {
    font-size: 70px;
    font-family: 'rawy';
    text-align: center;
  }

  img {
    width: 500px;
    height: 500px;
  }
}



</style>
