<template>
 <ul id="bottom-navigation">
    <li><router-link to="/">Home</router-link></li>
    <li><router-link to="/info">Info</router-link></li>
    <li><router-link to="/resume">Resume</router-link></li>
    <li><router-link to="/projects">Projects</router-link></li>
    <li><router-link to="/Links">Links</router-link></li>
    <li><router-link to="/Contact">Contact</router-link></li>
 </ul>
</template>

<style scoped>
    ul#bottom-navigation {
        background-color: #00FF00;
        list-style: none;
        display: flex;
        flex-direction: row;
        justify-content: center;
        align-items: center;
        flex-shrink: 0;
        margin: 0;
        padding: 0;
        height: 33px;
    }

    a {
        font-family: OCR-B-web;
        margin: 20px;
        text-decoration: none;
        animation: fade 1s ease infinite alternate;
        color: #000;
    }

    @keyframes fade {
        50% {
            color: #000;
        }

        100% {
            color: #FFF;
        }
    }




</style>