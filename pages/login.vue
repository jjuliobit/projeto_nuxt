<template>
    <div>
        <AppLogin />
        <AppFooter />
    </div>
</template>
  
<script>

import AppLogin from '../components/AppLogin.vue';
import AppFooter from '../components/AppFooter.vue';


export default {
    layouts: {
        name: 'Login',
    },
    components: {
        AppLogin,
        AppFooter,
    }

}
</script>
  
  
  