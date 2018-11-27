<template>
    <div :class="[btnClass, cname]">
        
    </div>
</template>

<script>
export default {
    props: {
        cname: {
            type: String,
            default: ''
        }
    },
    data () {
        return {
            btnClass: 'btn',
        }
    }
}
</script>

<style lang="scss">
@import '../../css/element';

.btn{
    @include btn;
}
</style>



