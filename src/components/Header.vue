<template>
    <header>
        <img src="/img/logo.svg" class="logo">
        <div class="coordinates text-blue-500 underline"><a href="mailto:corporation@world.org">corporation@world.org</a></div>
    </header>
</template>

<style scoped>
    header .coordinates {
        margin-right: 1rem;
    }

    header {
        display: flex;
        align-items: center;
        justify-content: space-between;
    }
    header .logo {
        width: 2rem;
        margin-left: 1rem;
    }
</style>
