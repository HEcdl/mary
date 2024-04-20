<template>
    <div>
        <h2>Contador: {{ count }}</h2>
        <button @click="increment">Incrementar</button>
       <!--  <button @click="zero">En Cero 0</button>
 -->        <!--  <button @click="decrement">Decrementar</button>
 -->
    </div>
</template>

<script>
export default {
    data() {
        return {
            count: 0
        }
    },
    methods: {
        increment() {
            this.count++
        },
        decrement() {
            this.count--
        }
      /*   zero(){
            
        } */
    }
}
</script>

<style scoped>

    h2 {
        color: black;
    }

</style>