<template>
    <nav class="flex justify-between items-center fixed w-full top-0 p-2 navbar">
        <div class="mr-5">
            <nuxt-link to="/" class="nav-link">المحتوى الرئيسى</nuxt-link>
           
        </div>
        <div>
            <nuxt-link to="/" class="flex items-center">
                <img src="~assets/images/logo.png" width="50px" alt="حياة الصحابة" />
                <h2 class="logo-brand mr-2">حياة الصحابة</h2>
            </nuxt-link>
        </div>
        <div class="ml-5">
            <nuxt-link to="/about" class="nav-link">عن الموقع</nuxt-link>
            <nuxt-link to="/contact" class="nav-link">اتصل بنا</nuxt-link>
        </div>
    </nav>   
</template>

<script>
export default {
    
}
</script>


<style lang="scss">
// can't import it in main.scss don't know why
@import '~assets/scss/variables';

.navbar {
    background-color: rgb(255, 226, 163);
    box-shadow: 0 1px 8px 0 #ccc;
}

.logo-brand {
    font-family: 'bs';
    color: $primary_color;
}

.nav-link {
    font-size: 1.2em;
    color: $primary_color;
    padding: 0px 10px;
    border-radius: 10px;
    transition: 0.2s ease-in;

    &:hover {
        background-color: $primary_color;
        color: #fff;
        transition: 0.2s ease-in;
    }
}



</style>