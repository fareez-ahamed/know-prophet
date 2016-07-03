<template>
    <div id="app">
        <a class="arrow left">&lt</a>
        <a class="arrow right">&gt</a>
    </div>
</template>

<script>
export default {

}
</script>

<style>
#app {
    position: absolute;
    top:0;
    left:0;
    right: 0;
    bottom: 0;
}

.arrow {
    position: absolute;
    top: 0;
    bottom: 0;
    width: 100px !important;
    height: 100%;
    text-align: center;
    vertical-align: middle;
}

.arrow:hover {
    background-color: #eee;
}

.left {
    left:0;
}

.right {
    right: 0;
}
</style>
