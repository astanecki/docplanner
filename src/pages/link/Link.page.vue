<template>
    <div class="link-page">
        <CreateWidget />
        <WidgetPreview />
    </div>
</template>

<script>
import CreateWidget from '@/design/patterns/createWidget/CreateWidget';
import WidgetPreview from '@/design/patterns/widgetPreview/WidgetPreview'

export default {
    components: {
        CreateWidget,
        WidgetPreview,
    },
}
</script>

<style lang="scss" scoped>
.link-page {
    padding: 20px 10px 10px 10px;
}
</style>