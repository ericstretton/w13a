<template>
    <div id="bodyGrid">
        <MeetTheTeam/>
        <BodyMeetTheDeveloper/>
        <RandomSidePanel/>

    </div>
</template>

<script>
import BodyMeetTheDeveloper from './BodyMeetTheDeveloper.vue'
import MeetTheTeam from './MeetTheTeam.vue'
import RandomSidePanel from './RandomSidePanel.vue'
    export default {
  components: { BodyMeetTheDeveloper,
                MeetTheTeam,
                RandomSidePanel },
        
    }
</script>

<style scoped>
#bodyGrid{
    display: grid;
    grid-template-columns: 1fr 1fr 1fr;
}
#meetTheDeveloper{
    display: grid;
    grid-template-rows: 1fr 1fr;
    grid-template-columns: 1fr 1fr 1fr;
}


</style>