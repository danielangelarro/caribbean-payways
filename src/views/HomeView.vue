<script setup>
import Ellipse from '../components/Ellipse.vue';

const advice = '¡Pronto llegará Caribbean Payways, la nueva pasarela de pago para la región del Caribe!';
const paragraph = "¿Estás buscando una forma rápida, segura y conveniente de realizar tus \
transacciones en línea? ¡Caribbean Payways está aquí para hacerte la vida más \
fácil! Con tecnología de vanguardia y una interfaz intuitiva, Caribbean Payways se \
convertirá en tu perfecta herramienta para todas tus necesidades de pago \
en línea.";
const show = true;
</script>

<template>

    <Ellipse :advice="advice" :paragraph="paragraph" :show="show"/>

</template>

<style scoped>

</style>

