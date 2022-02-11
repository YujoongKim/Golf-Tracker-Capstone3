<template>
<div class="match">
    <div id="previous-matches-div">
        <previous-matches />
    </div>

    <div id="match-scores-div">
    <create-match />
    <add-match-score/>
    </div>

    <div id="upcoming-matches-div">
        <upcoming-matches />
    </div>

</div>
</template>

<script>
import AddMatchScore from '../components/AddMatchScore.vue';
import CreateMatch from '../components/CreateMatch.vue';
import PreviousMatches from '../components/PreviousMatches.vue';
import UpcomingMatches from '../components/UpcomingMatches.vue';


export default {
    components: { CreateMatch, AddMatchScore, PreviousMatches, UpcomingMatches },
    name: "match",

}
</script>

<style scoped>
.match {
    width: 100vw;
    height: 80vh;
    display: flex;
    justify-content: space-between;
    padding: 20px;
    align-content: center;
}

#previous-matches-div,
#upcoming-matches-div {
    width: 20vw;
    height: 60vh;
}




</style>>
