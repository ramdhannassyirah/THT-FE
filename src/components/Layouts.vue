<script setup>
import FooterComp from './common/FooterComp.vue';
import NavbarComp from './common/NavbarComp.vue';
</script>
<template>
    <header>
        <NavbarComp/>
    </header>
    <main>
        <slot/>
    </main>
    <footer>
        <FooterComp/>
    </footer>

</template>