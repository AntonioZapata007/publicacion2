<template>
    <div class="container mt-3">
        <h1>Mi primer componente con VUE</h1>
        <h2 :class="contador > 10 ? 'text-success' : 'text-danger'">{{ contador }}</h2>
        <button type="button" class="btn btn-primary" @click="decrementar()">decrementar</button>
        <button type="button" class="btn btn-danger" @click="contador++">incrementar</button>
        <br>
        <ul>
            <li class="text-success" v-for="(item, indice) in colores" :key="indice">{{ item }}</li>
        </ul>
    </div>
</template>
<script>
import { ref } from 'vue'
export default {
    setup() {
        const contador = ref(0);
        const colores = ref(['Amarillo', 'Verde', 'Negro', 'Blanco'])
        const decrementar = () => {
            if (contador.value > 1) {
                contador.value--;
            }
        }
        return {
            contador,
            decrementar,
            colores

        }

    }

}
</script>
<style></style>