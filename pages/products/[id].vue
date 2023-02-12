<template>
    <div>
        Продукт номер {{ id }}
    </div>
    <div>Lorem ipsum dolor sit amet consectetur adipisicing elit. Harum voluptatem eligendi a praesentium ad recusandae at? Nostrum quibusdam sit odio. Fuga quisquam eveniet labore commodi architecto distinctio provident vel dolore!</div>
</template>

<script setup>
definePageMeta({
    layout: 'products'
})
const { id } = useRoute().params
</script>