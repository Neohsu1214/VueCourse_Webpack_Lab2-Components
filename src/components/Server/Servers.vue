<template>
    <div class="col-xs-12 col-sm-6">
        <ul class="list-group">
            <li
                    class="list-group-item"
                    v-for="index in 5" :key="index">
                Server #{{ index }}
            </li>
        </ul>
    </div>
</template>

<script>
</script>

<!-- 如果不想讓CSS定義影響到整個Vue instance的話，記得在 component 的 style 加上 "scoped" -->
<style scoped>
    div {
        border: 1px solid blue;
    }
</style>
