<template>
    <div>
        <TheCompany/>
        <Excellence/>
        <ProcessManagement/>
        <Team/>
        <LatestNews/>
    </div>
</template>

<script>
import TheCompany from './TheCompany.vue'
import Excellence from './Excellence.vue'
import ProcessManagement from './ProcessManagement.vue'
import Team from './Team.vue'
import LatestNews from './LatestNews.vue'


export default {
    name : 'IndexMain',
    components : {
        TheCompany,
        Excellence,
        ProcessManagement,
        Team,
        LatestNews
    }
}
</script>

<style>

</style>