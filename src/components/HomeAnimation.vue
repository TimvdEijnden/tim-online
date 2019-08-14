<template>
    <div>
       <svg xmlns="http://www.w3.org/2000/svg" viewBox="0 0 130.7 158.05" width="300"><g id="t-logo"><path class="outline" d="M139.15,39.08C93,33,69.21,28.45,38.61,9.12L13.44,39.47S66.31,30.42,139.15,39.08Z" transform="translate(-10.94 -6.62)"/><path class="outline" d="M84,162.18l22.64-20s-6.29-41.23,1-80.86A157.79,157.79,0,0,0,84,58.77S76.3,103.87,84,162.18Z" transform="translate(-10.94 -6.62)"/><path class="outline" d="M107.67,61.34c13.57,2.48,13.69,2.46,31.48,7.74v-30" transform="translate(-10.94 -6.62)"/><path class="outline" d="M54.75,111.27c0,29.18-2.29,50.91-2.29,50.91H84" transform="translate(-10.94 -6.62)"/><path class="outline" d="M13.44,39.47v35.4a134.41,134.41,0,0,1,16.3-7.07" transform="translate(-10.94 -6.62)"/><path class="outline" d="M54.75,111.27A467.07,467.07,0,0,0,52.46,63.6c-6.9-.58-15.41,1.61-22.72,4.2" transform="translate(-10.94 -6.62)"/></g></svg>
    </div>
</template>

<style scoped>

div {
    text-align: center;
}

.outline {
    fill: none;
    stroke: #57b436;
    stroke-linecap: round;
    stroke-linejoin: round;
    stroke-width:5px;
}

svg {
   animation: rotate 2s ease-in-out infinite;
}

@keyframes rotate {
    0% {
        transform: rotate(0deg);
    }

    80% {
        transform: rotate(360deg);
    }

    100% {
        transform: rotate(360deg);
    }
}
</style>