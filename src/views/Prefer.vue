<template>
    <div>
        <h2>Which style of fishing do you prefer?</h2>
            <b-form-group label="Fishing Styles:">
            <b-form-checkbox-group
                switch size="lg"
                class="mb-4"
                v-model="selected"
                :options="options"
                switches
                stacked
            ></b-form-checkbox-group>
        </b-form-group>
        <b-button to="/prefer1" block variant="outline-success">Step 2: Fishing Location Preferences</b-button>
    </div>
</template>

<script>
export default {
  data () {
    return {
      selected: [], // Must be an array reference!
      options: [
        { text: 'Fly Fishing', value: 'fly fishing' },
        { text: 'Bait Fishing', value: 'bait fishing' },
        { text: 'Spinning', value: 'spinning' },
        { text: 'Bait Casting', value: 'bait casting' },
        { text: 'Trolling', value: 'trolling' }
      ]
    }
  }
}
</script>
