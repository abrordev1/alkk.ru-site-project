<template>
    <div class="home-page">
        <h1>Home Page</h1>
        <TheButton>Оставить заявку</TheButton>
        <TheTitle>Продвижение сайтов</TheTitle>
    </div>
</template>

<script>
import TheButton from '../../ui/TheButton.vue';
import TheTitle from '../../ui/TheTitle.vue'


export default {
    components: { TheButton, TheTitle }
}

</script>