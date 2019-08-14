<template>
    <h1>{{$route.name}}</h1>
</template>

<style scoped>
h1 {
    text-transform: capitalize;
    font: bold 40px OCR-B-web;
    animation: fadeMove .5s linear infinite alternate;
}

@keyframes fadeMove {
    0% {
        color: #00FF00;
        margin-top: 0px;
        margin-bottom:30px;
    }

    100% {
        color: #000;
        margin-top: 10px;
        margin-bottom: 20px;
    }
}
</style>
