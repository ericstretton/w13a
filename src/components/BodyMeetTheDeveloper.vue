<template>
    <div id="meetTheDeveloper">
        <h1>MEEEEET THE DEVELOPER</h1>
        <p>Who made this garbage?</p>
        <h2>Eric Stretton</h2>
        <p>You're welcome!</p>
    </div>
</template>

<script>
    export default {
        
    }
</script>

<style scoped>
*{  padding: 0;
    margin: 0;
    background-color: aqua;
    position: relative;
}
h1{
    margin: 0;
    padding: 0;
    display: inline-block;
    grid-column-start: 1;
    grid-column-end: 4;
    font-size: 1.8em;
    top: 3vh;
}
p{
    grid-row: 2;
    top: 3vh;
}
h2{
    grid-column: 2;
    grid-row: 2;
    top: 2vh;
}
</style>