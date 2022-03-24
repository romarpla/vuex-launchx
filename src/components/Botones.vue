<template>
    <div class="botones">
      <button @click="$store.dispatch('bajarContador')">-</button>
      <button @click="$store.dispatch('subirContador')">+</button>
    </div>
</template>

<script>
export default {
  name: 'Botones',
}
</script>
