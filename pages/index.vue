<template>
<main>

  <section class="landing flex justify-around items-center mt-4">
    <div>
      <h1>السير فى خطى الصحابة</h1>
      <h1 class="text-orange-500">رضي الله عنهم</h1>
    </div>
    <img src="@/assets/images/logo.png" alt="hayat al-sahaba" />
  </section>
  <section class="top-ten mt-20">
    <h1 class="text-orange-500">العشرة المبشرين بالجنة</h1>
    <div class="flex justify-around">
      <ul>
        <li>1. أبو بكر الصديق</li>
        <li>3. عثمان بن عفان</li>
        <li>5. طلحة بن عبيد الله</li>
        <li>7. عبد الرحمن بن عوف</li>
        <li>9. سعد بن أبى وقاص</li>
      </ul>
      <ul>
        <li>2. عمر بن الخطاب</li>
        <li>4. على بن أبى طالب</li>
        <li>6. الزبير بن العوام</li>
        <li>7. سعيد بن زيد</li>
        <li>10. أبو عبيدة بن الجراح</li>
      </ul>
    </div>
  </section>
</main>
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

.landing { 
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

.top-ten {
  h1 {
    font-size: 60px;
    font-family: 'rawy';
    text-align: center;
  }
  ul {
    margin: 30px 0;
    li {
        font-size: 30px;
        margin-top: 15px;
    }
  }
}


</style>
