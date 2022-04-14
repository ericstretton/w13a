<template>
    <div>
        <p>Let's see what cool stuff we can put in here</p>
        <BodyMeetTheDeveloper/>
    </div>
</template>

<script>
import BodyMeetTheDeveloper from './BodyMeetTheDeveloper.vue'
import BodyMeetTheDeveloperVue from './BodyMeetTheDeveloper.vue'
    export default {
  components: { BodyMeetTheDeveloper },
        BodyMeetTheDeveloperVue,
    }
</script>

<style scoped>
*{
    display: grid;
    grid-template-rows: 1fr 1fr;
    grid-template-columns: 1fr 1fr 1fr;
}
p{
    grid-row-start: 0;
    grid-column-start: 0;
    grid-column-end: 3;
}

</style>