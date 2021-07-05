<template>
  <div>
    <b-nav pills class="flex justify-content-center">
      <b-nav-item
        id="milestoneTwo"
        @click="onMilestoneTwo"
        :active="activeMilestoneTwo"
				href="#scrollSpace"
        >Milestone 2</b-nav-item
      >
      <b-nav-item
        id="milestoneThree"
        @click="onMilestoneThree"
        :active="activeMilestoneThree"
				href="#scrollSpace"
        >Milestone 3</b-nav-item
      >
      <b-nav-item
        id="milestoneFour"
        @click="onMilestoneFour"
        :active="activeMilestoneFour"
				href="#scrollSpace"
        >Milestone 4</b-nav-item
      >
    </b-nav>

		<!-- Actual milestone content -->
		<p id="scrollSpace"></p>
		<MilestoneTwo v-show="activeMilestoneTwo" />
		<MilestoneThree v-show="activeMilestoneThree" />
		<MilestoneFour v-show="activeMilestoneFour" />
	  </div>
</template>

<script>
export default {
  name: "NavTabs",

  data() {
    return {
      activeMilestoneTwo: false,
      activeMilestoneThree: false,
			activeMilestoneFour: false,
    };
  },

  methods: {
		onMilestoneTwo()  {
			this.activeMilestoneTwo = !this.activeMilestoneTwo;
			this.activeMilestoneThree = false;
			this.activeMilestoneFour = false;
		},

    onMilestoneThree() {
      this.activeMilestoneTwo = false;
      this.activeMilestoneThree = !this.activeMilestoneThree;
			this.activeMilestoneFour = false;
    },

		onMilestoneFour() {
			this.activeMilestoneTwo = false;
			this.activeMilestoneThree = false;
			this.activeMilestoneFour = !this.activeMilestoneFour;
		},

		deactivate() {
			this.onMilestoneTwo = false;
		},
		
  },
};
</script>

<style>
</style>