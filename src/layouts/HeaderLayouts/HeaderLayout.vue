<template> 
    <header class="header py-4">
        <div class="container flex items-center justify-between">
            <HeaderLogo></HeaderLogo>
             <HeaderMenu></HeaderMenu>
             <HeaderContacts></HeaderContacts>

        </div>

    </header>

</template>

<script>
import HeaderContacts from './components/HeaderContacts.vue';
import HeaderLogo from './components/HeaderLogo.vue';
import HeaderMenu from './components/HeaderMenu.vue';


export default {
    components: { HeaderLogo, HeaderMenu, HeaderContacts }
}

</script>