<template>
    <div>
        <h2>Which type of fish do you like to catch?</h2>
            <b-form-group label="Plain stacked checkboxes">
            <b-form-checkbox-group
                size="lg"
                v-model="selected"
                :options="options"
                plain
                stacked
            ></b-form-checkbox-group>
        </b-form-group>
        <b-button to="/profile" block variant="outline-success">Finish</b-button>
    </div>
</template>

<script>
export default {
  data () {
    return {
      selected: [], // Must be an array reference!
      options: [
        { text: 'Large Mouth Bass', value: 'largemouthbass' },
        { text: 'Small Mouth Bass', value: 'smallmouthbass' },
        { text: 'Rainbow Trout', value: 'rainbowtrout' },
        { text: 'Striped Bass', value: 'stripedbass' },
        { text: 'Black Sea Bass', value: 'blackseabass' },
        { text: 'Flounder', value: 'flounder' },
        { text: 'Mackerel', value: 'mackerel' },
        { text: 'Tunas', value: 'tuna' },
        { text: 'Cod', value: 'cod' },
        { text: 'Smelts', value: 'smelts' }
      ]
    }
  }
}
</script>
