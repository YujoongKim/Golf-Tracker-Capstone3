<template>
  <div id="leagues">
    <create-league />

    <display-league/>
  </div>
</template>

<script>
import CreateLeague from "../components/CreateLeague.vue";
// import DisplayAllLeague from "../components/DisplayLeague"
import DisplayLeague from '../components/DisplayLeague.vue';
export default {
  components: {  CreateLeague, DisplayLeague },
};
</script>

<style>
#leagues {
  background-color: #f7ecde;
  padding: 20px;
  border-radius: 10px;
  margin: 0 auto;
  display: flex;
  height: 50%;
  width: 50%;
  justify-content: space-between;
}

</style>