<script setup>
defineProps(['advice','paragraph','show'])
</script>

<template>

    <div class="ellipse1">
        <div class="content">
            <img alt="logo" class="logo" src="@/assets/logo.svg" width="75%" height="125" />
            <div class="advice">
                {{ advice }}
            </div>
            <div class="paragraph">
                {{ paragraph }}
            </div>
            <form action="" v-if="show">
                <input type="text" placeholder="Introduzca su dirección de correo">
                <button>Unirme a la lista de espera</button>
            </form>
        </div>
    </div>     

</template>