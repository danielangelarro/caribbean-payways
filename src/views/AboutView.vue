<script setup>
import Ellipse from '../components/Ellipse.vue';

const advice = '¡Pronto llegará Caribbean Payways, la nueva pasarela de pago para la región del Caribe!';
const paragraph = "Cuando lancemos Caribbean Payways le enviaremos un correo de notificación. ¡Estamos en contacto!";
const show = false;
</script>

<template>

    <Ellipse :advice="advice" :paragraph="paragraph" :show="show"/>

</template>

<style scoped>

</style>

