<script>
import Profile from './components/Profile.vue';
import Education from './components/Education.vue';
import Skills from './components/Skills.vue';

export default {
    name: "app",
    components: {
        Profile,
        Education,
        Skills,
    },
};

</script>

<template>
    <div class="app-container">
        <Profile />
        <Education />
        <Skills />
    </div>

    
</template>

<style scoped>
.app-container
{
    height: 100vh;
    display: flex;
    align-items: center;
    flex-direction: column;
    color: #000;
    margin: 4%;
}


    
</style>