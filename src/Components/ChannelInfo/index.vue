<template>
    <div class="container">
        <div class="icon">
            <HashtagIcon :size="24" />
        </div>
        <h1 class="title">chat-livre</h1>
        <div class="separator"></div>
        <div class="description">Canal aberto para conversas</div>
    </div>
</template>

<script>
import HashtagIcon from "vue-material-design-icons/Pound.vue";
export default {
    components:{
        HashtagIcon
    }
}
</script>

<style lang="scss" scoped>
.container{
    grid-area: CI;
    background-color: var(--primary);
    display: flex;
    align-items: center;
    padding: 0 17px;
    box-shadow: rgba(0,0,0,.9) 0 1px 0 0;
    z-index: 2;
}
.title{
    color: var(--white);
    font-size: 16px;
    margin-left: 9px;
    font-weight: bold;
}

.description {
    color: var(--grey);
    font-size: 15px;
}

.separator {
    background: var(--white);
    height: 24px;
    width: 1px;
    opacity: .2;
    margin: 0 13px;
}
.icon {
    color: var(--symbol);
}
</style>