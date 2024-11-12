<template>
    <dev class="container">
        <slot />
        <footer> &copy; proglus.jp</footer>
    </dev>
</template>
<style>
.container {
    color: red;
}
footer {
    background-color: orange;
    color: white;
    text-align: center;
}
</style>