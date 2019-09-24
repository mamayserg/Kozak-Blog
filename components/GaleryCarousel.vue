<template>
    <div>
        <carousel :data="data" :controls="true"></carousel>
    </div>
</template>

<script>
    export default {
        name: "GaleryCarousel",
        data() {
            return {
                data: [
                    '<div class="example-slide">Slide 1</div>',
                    '<div class="example-slide">Slide 2</div>',
                    '<div class="example-slide">Slide 3</div>',
                ],
            };
        },
    }
</script>

<style scoped>

</style>