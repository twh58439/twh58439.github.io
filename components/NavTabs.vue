<template>
  <b-card no-body>
    <b-tabs pills fill card content-class="tab-content">
      <b-tab title="Milestone 2" active>
        <b-card-text>
          <MilestoneTwo />
        </b-card-text>
      </b-tab>
      <b-tab title="Milestone 3">
        <b-card-text>
          <MilestoneThree />
        </b-card-text>
      </b-tab>
      <b-tab title="Milestone 4">
        <b-card-text>
          <MilestoneFour />
        </b-card-text>
      </b-tab>
    </b-tabs>
  </b-card>
</template>

<style>
.tab-content {
  height: 75vh;
  overflow-y: scroll;
  overflow-x: hidden;
}
</style>