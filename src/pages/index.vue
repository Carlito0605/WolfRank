<script setup lang="ts">
</script>

<template>
  <div class="relative">
    <Header />

    <div class="w-full flex flex-col justify-start items-center">
      <div class="mt-20" />
      <ReportMatchButton class="mt-8" />
      <h1 class="mt-8 mb-4">
        Classements récents
      </h1>
      <RankingDisplay class="mb-4" ranking="Wolfgang" placement="3e" players="70" />
      <RankingDisplay class="mb-4" ranking="ESGI/Smash" placement="1er" players="20" />
      <RankingDisplay class="mb-4" ranking="ESGI/MarioKart" placement="3e" players="10" />
      <RankingDisplay class="mb-4" ranking="ESGI/MarioParty" placement="6e" players="15" />
      <RankingDisplay class="mb-4" ranking="All" placement="3e" players="20" />
      <SeeMoreButton />
      <h1 class="mt-10 mb-4">
        Vos derniers matchs
      </h1>
      <MatchDisplay class="mb-4" tournament="Session chez Anthony" date="23/03/2023" player1="Dr.Mustapha" player2="Jekiru" score1="0" score2="2" />
      <MatchDisplay class="mb-4" tournament="Melt Bros Ultimate #57" date="10/03/2023" player1="Dr.Mustapha" player2="Greewiind" score1="1" score2="2" />
      <MatchDisplay class="mb-4" tournament="Session chez Anthony" date="1/03/2023" player1="Dr.Mustapha" player2="Jekiru" score1="0" score2="2" />
      <MatchDisplay class="mb-4" tournament="Melt Bros Ultimate #56" date="27/02/2023" player1="Dr.Mustapha" player2="Miakos" score1="1" score2="2" />
      <MatchDisplay class="mb-4" tournament="Ladder Reset" date="15/02/2023" player1="Dr.Mustapha" player2="Shaka" score1="3" score2="0" />
      <SeeMoreButton />
      <div class="mb-20" />
    </div>

    <TheFooter />
  </div>
</template>
