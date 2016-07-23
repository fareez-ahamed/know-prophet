<template>
    <div class="slide">
        <a class="arrow">&lt</a>
        <div class="quote">
            Bismillah
        </div>
        <a class="arrow">&gt</a>
    </div>
</template>

<script>
export default {

}
</script>

<style>
.slide {
    position: absolute;
    display: flex;
    align-items: center;
    justify-content: center;
    top:0;
    bottom: 0;
    left: 0;
    right: 0;
}

.quote {
    flex-grow: 4;
    text-align: center;
    padding:50px;
}

.arrow {
    padding:30px;
}

.arrow:hover {
    background-color: #eee;
}
</style>
