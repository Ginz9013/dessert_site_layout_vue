<script>
</script>
<template>
    <header>
        <div class="logo"></div>
        <div class="nav"></div>
    </header>
</template>
<style lang="scss" scoped>
header {
    padding: 2rem;
    display: flex;
    justify-content: space-between;
    align-items: center;

    .logo {
        width: 100px;
        height: 100px;
        background-color: #D38282;
        cursor: pointer;
    }

    .nav {
        width: 60px;
        height: 8px;
        background-color: #222;
        position: relative;
        border-radius: 4px;

        &::before, &::after {
            content: "";
            width: inherit;
            height: inherit;
            background-color: inherit;
            position: absolute;
            border-radius: inherit;
        }

        &::before {
            top: 20px;
        }

        &::after {
            top: -20px;
        }

        &, &::before, &::after {
            cursor: pointer;
        }
    }
}

</style>