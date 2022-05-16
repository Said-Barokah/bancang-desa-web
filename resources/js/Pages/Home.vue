<template>
    <navbar></navbar>
    <image-slide></image-slide>
</template>
<script>
    import Navbar from './Components/Home/Navbar.vue';
    import ImageSlide from './Components/Home/ImageSlide.vue';

    export default {
        components: {
            Navbar,
            ImageSlide
        },

        data() {
            return {
                messages: [{

                }]
            }
        }
    }

</script>
