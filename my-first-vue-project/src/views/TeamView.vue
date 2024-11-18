<script setup>
import TeamFooter from "@/components/Team/TeamFooter.vue";
import TeamHeader from "@/components/Team/TeamHeader.vue";
import TeamMembers from "@/components/Team/TeamMembers.vue";
import { useTeamStore } from "@/stores/TeamStore";

let team = useTeamStore();

team.fill();

setTimeout(() => {
  team.grow(25);
}, 2000);
</script>

<template>
  <TeamHeader />
  <div class="place-self-center flex flex-col gap-y-3" style="width: 725px">
    <TeamMembers />


  </div>

  <TeamFooter />
</template>
