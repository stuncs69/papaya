<template>
    <header>
        <div class="empty" />
        <div>
            <h2>Papaya.js</h2>
        </div>
        <div class="empty" />
        <div>

        </div>
    </header>
</template>

<style lang="scss" scoped>

header {
    position: -webkit-sticky;
    position: sticky;
    top: 0;
    width: 100%;
    background-color: #24242440;
    backdrop-filter: blur(1rem);
    height: 5rem;
    display: flex;
    flex-direction: row;
    justify-content: space-around;
    > div:first-child {
        h2 {
            line-height: 5rem;
            padding: 0;
            margin: 0;
        }
    }
}

</style>