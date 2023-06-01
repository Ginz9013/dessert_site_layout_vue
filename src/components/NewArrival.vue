<script setup>
</script>
<template>
    <div class="new-arrival">
        <div class="bg"></div>
        <img src="../assets/img/Rectangle 12.png" alt="">
        <div class="text-area">
            <h3>New Arrival</h3>
            <p>Lorem ipsum dolor sit amet consectetur adipisicing elit. Quas doloribus, corrupti quaerat est harum qui?</p>
        </div>
    </div>
</template>
<style lang="scss" scoped>
.new-arrival {
    display: flex;
    padding: 3rem 0;
    position: relative;

    img {
        width: 65%;
        z-index: 1;
    }
    
    .text-area {
        background-color: #F7CDC0;
        margin-left: 2rem;
        padding: 1.5rem;
        padding-top: 4rem;

        h3 {
            margin-bottom: 2rem;
        }
    }

    .bg {
        background-color: #E49E9E;
        height: 100%;
        width: 2000px;
        position: absolute;
        top: 0;
        right: 50%;
        z-index: 0;
    }
}
</style>