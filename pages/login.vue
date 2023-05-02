<template>
    <div>
        <AppHeader />
        <AppLogin />
        <AppFooter />
    </div>
</template>
  
<script>
import AppHeader from '../components/AppHeader.vue';
import AppLogin from '../components/AppLogin.vue';
import AppFooter from '../components/AppFooter.vue';


export default {
    layouts: {
        name: 'Login',
    },
    components: {
        AppHeader,
        AppLogin,
        AppFooter
    }

}
</script>
  
  
  