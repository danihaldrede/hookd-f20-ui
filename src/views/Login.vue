<template>
    <div>
        <Signin/>
        <b-input-group size="lg" class="mb-4">
            <b-input-group-prepend is-text>
                <b-icon icon="person-circle"></b-icon>
            </b-input-group-prepend>
            <b-form-input type="text" placeholder="Enter Username"></b-form-input>
        </b-input-group>
        <b-input-group size="lg" class="mb-4">
            <b-input-group-prepend is-text>
                <b-icon icon="person-fill"></b-icon>
            </b-input-group-prepend>
            <b-form-input type="text" placeholder="Enter Name"></b-form-input>
        </b-input-group>
        <b-input-group size="lg" class="mb-4">
            <b-input-group-prepend is-text>
                <b-icon icon="envelope-fill"></b-icon>
            </b-input-group-prepend>
            <b-form-input type="text" placeholder="johndoe1@gmail.com"></b-form-input>
        </b-input-group>
        <b-input-group size="lg" class="mb-4">
            <b-input-group-prepend is-text>
                <b-icon icon="file-lock2"></b-icon>
            </b-input-group-prepend>
            <b-form-input type="text" placeholder="Enter a Password"></b-form-input>
        </b-input-group>
        <b-button to="/home" variant="outline-success" class="mb-5">Sign In</b-button>
    <div class="my-6">Don't have an account?</div>
        <b-button to="/signup" variant="outline-success" class="my-1">Sign up</b-button>
</div>
</template>

<style>

</style>
