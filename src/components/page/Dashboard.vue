<template>
  <div>

  </div>
</template>

<script>
import bus from '../common/bus';
export default {
    name: 'dashboard',
    data() {
        return {};
    },
    components: {

    },
    computed: {
        role() {
            return this.name === 'admin' ? '超级管理员' : '普通用户';
        }
    },

    methods: {}
};
</script>


<style scoped>

</style>
