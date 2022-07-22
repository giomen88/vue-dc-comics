<template>
    <main>
        <div id="content">
            <div class="container">
            CONTENT GOES HERE
            </div>
        </div>
    </main>
</template>

<script>
export default {
    name: 'TheContent',
}
</script>

<style lang="scss" scoped>
main {
    flex-grow: 1;

    #content {
    height: 160px;
    background-color: black;
    color: white;
    }
}
</style>