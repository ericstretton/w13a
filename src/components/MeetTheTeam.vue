<template>
    <div id="meetTheTeam">
        <img src="https://spng.pinpng.com/pngs/s/39-397316_rick-and-morty-clipart-beth-rick-and-morty.png" alt="beth"/>
        <img id="mrP" src="https://mpng.subpng.com/20180723/kjv/kisspng-sticker-television-decal-clip-art-rick-and-morty-character-5b55773983c6c6.5171271115323277375398.jpg" alt="mrP">
        <img src="https://www.pinpng.com/pngs/m/560-5602058_topet3-rick-and-morty-characters-morty-hd-png.png" alt="morty">
        <img src="https://banner2.cleanpng.com/20180712/ilo/kisspng-rick-sanchez-morty-smith-pickle-rick-rick-and-mort-scary-terry-5b47a4425dea10.9176037915314217623847.jpg" alt="pickles">
        <img id="summer" src="https://i.pinimg.com/564x/93/3f/ce/933fce7bf2db6fed7b2a38569fd5f7c4.jpg" alt="summer">
        <img id="mary" src="https://mpng.subpng.com/20180810/zpw/kisspng-mary-image-portable-network-graphics-decal-clip-ar-glanzbilder-victorian-die-cut-victorian-scrap-5b6d5f5bc08545.4562776615338944917886.jpg" alt="maryLOL">
    </div>
</template>

<script>
    export default {
        
    }
</script>

<style scoped>
#meetTheTeam{
    display: grid;
    grid-template-rows: 1fr 1fr;
    grid-template-columns: 1fr 1fr 1fr;
}
#mrP{
    height: 12vh;
    width: auto;
}
#summer{
    width: 11vw;
    position: absolute;
    top: 47vh;
    left: 11vw;
}
#mary{
    position: relative;
    left: 4vw;
    width: 3vw;
    grid-column: 3;
}
img{
    width: 10vw;
}

</style>