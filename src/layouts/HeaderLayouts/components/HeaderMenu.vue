<template>
    <div class="header-menu">
       <ul class="menu flex gap-6 text-dark ">
            <li class="text-sm font-[FiraSansExtraCondensed] font-medium hover:text-red cursor-pointer duration-300 " v-for="item in menuItems" :key="item">
                {{ item.name }}
            </li>
       </ul>
    </div>
</template>

<script> 

import menuList from '../MenuList.js'

export default {
    data() {
        return {
            menuItems: menuList
        }
    }
}

</script>