<template>
    <div :class="[btnClass,cname]">
        <slot/>
    </div>
</template>

<script>
export default {
    props: {
        cname: {
            type: String,
            defalut: '',
        }
    },
    data() {
        return {
            btnClass: 'btn',
        }
    }
}
</script>

<style lang="scss">
@import "../../css/element.scss";
.btn {
    @include btn;
}
</style>
