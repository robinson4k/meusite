<template>
    <div>
      <font-awesome-icon :icon="icon" />
    </div>
</template>
  
<script setup>
    import { defineProps } from 'vue'
    import { FontAwesomeIcon } from '@fortawesome/vue-fontawesome'
    import { faCoffee } from '@fortawesome/free-solid-svg-icons'
    
    const props = defineProps({
        icon: {
        type: Object,
        default: faCoffee
        }
    })
</script>