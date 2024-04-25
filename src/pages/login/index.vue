<!-- eslint-disable vue/multi-word-component-names -->
<template lang="">
    <div class="mt-4">
        <b-form @submit.prevent="onSubmit">
        <b-form-group
            id="input-group-1"
            label="Email address:"
            label-for="input-1"
            description="We'll never share your email with anyone else."
        >
            <b-form-input
            id="input-1"
            v-model="form.email"
            type="email"
            placeholder="Enter email"
            required
            ></b-form-input>
        </b-form-group>

        <b-form-group id="input-group-2" label="Password:" label-for="input-2">
            <b-form-input
            id="input-2"
            type="password"
            v-model="form.password"
            placeholder="******"
            required
            ></b-form-input>
        </b-form-group>

    

        <b-button type="submit" variant="primary">Login</b-button>
        
        </b-form> 
    </div>
</template>
<script>
export default {
    data(){
        return {
            form : {
                email : '',
                password : ''   
            }
        }
    },
    methods:{
        onSubmit () {

        }
    }
}
</script>
<style lang="">
    
</style>