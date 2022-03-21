<template>
    <div class="border border-personalized reason-card p-4 mx-4 py-5">
        <i :class="icon"></i>
        <h4 class="pt-4">{{ title }}</h4>
        <p class="small pt-1 page-description">{{ description }}</p>
    </div>
</template>

<script>
export default {
    name: 'ReasonCard',
    props: {
        icon: String,
        title: String,
        description: String
    }
}
</script>

<style>
.border-personalized {
    border-color: #F4F6FB;
    border-radius: 10px;
}
.reason-card {
    width: 15em;
    min-height: 22em;
}
</style>