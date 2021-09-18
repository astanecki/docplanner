<template>
   <div class="create-link">
        <b-card 
            :title="translatios.CREATE_YOUR_WIDGET" 
            :sub-title="translatios.CONNECT_DOCPLANNER_WITH_YOUR_WEBSITE"
        >
        </b-card>
    </div>
</template>

<script>
import translatios from '@/services/i18nService';

export default {
    data() {
        return {
            translatios: translatios.WIDGET,
        }
    }
}
</script>

<style lang="scss" scoped>
.create-link {
    /* todo */
    width: 550px; 
    text-align: left
}
</style>