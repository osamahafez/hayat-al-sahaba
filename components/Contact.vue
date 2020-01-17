<template>
    <main>
        <h1 class="text-center mt-3">إتصل بنا</h1>
        
        <div class="form-container">
            <form>
                <input type="text" v-model="name"  placeholder="الإسم" />                
                <input type="email" v-model="email" placeholder="البريد الإلكترونى" />
                <textarea v-model="message" rows="6"></textarea>
                <button @click.prevent="submitContactForm()">إرسال</button>                
            </form>
        </div>
    </main>   
</template>

<script>
export default {
    data() {
        return {
            name: null,
            email: null,
            message: null
        };
    },
    methods: {
        submitContactForm() {
            console.log(this.name, this.email, this.message);
        }
    }
}
</script>

<style lang="scss">
    @import '~assets/scss/variables';
    h1 {
        font-family: 'rawy';
        color: $primary_color;
    }
    .form-container {
        background-color: #fff;
        max-width: 500px;
        margin: 20px auto;
        padding: 20px;
        box-shadow: 0px 3px 10px -4px rgba(5,1,5,0.63);

        input {
            margin-right: 10px;
            margin-bottom: 10px;
            padding: 5px;
            width: 100%;
            border-bottom: 2px solid $primary_color;
            outline: none;    
        }

        textarea {
            margin-top: 20px;
            width: 100%;
            border-radius: 30px;
            background-color: rgb(217, 237, 248);
            padding: 20px;
            outline: none;
        }

        button {
            display: block;
            padding: 10px;
            background-color: $primary_color;
            color: #fff;
            font-size: 18px;
            width: 100%;
            border-radius: 5px;
            margin-top: 10px;

            &:hover {
                background-color: #095575;
            }
        }

    }
</style>