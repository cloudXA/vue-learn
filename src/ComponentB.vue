
<script>
    // 将ComponentA 和 ComponentC 导入到ComponetB模块中使用 

    import ComponentA from './ComponentA.vue'
    import ComponentC from './ComponentC.vue'


    export default {
        components: {
            ComponentA,
            ComponentC
        }
    }
</script>

