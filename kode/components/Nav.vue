<template>
    <div>
        <v-app-bar
            color="surface"
            height="78"
            class=""
            app
            :style="{padding: $vuetify.breakpoint.mdAndUp ? '0px 100px' : '' }"
        ></v-app-bar>
        
    </div>
</template>

<script>
import Default from '~/layouts/default.vue';
export default {
    components: { Default }
};
</script>
<style>
    
</style>