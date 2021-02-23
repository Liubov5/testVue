<template>
    <div>
        <img class="w-100" v-bind:src="address" alt="">
        <div class="col-2">
            Описание
        </div>
    </div>
</template>
<script>
export default {
    name: 'Menu',
    props: {
        address: String
    }
}
</script>
