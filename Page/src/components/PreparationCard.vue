<template>
    <div class="border d-flex flex-row justify-content-between align-items-center py-3 my-2 card-preparation">
        <div class="d-flex flex-row align-items-center">
            <div class="mx-2">
                <i :class="icon"></i>
            </div>
            <h4 class="reason-title">{{ title }}</h4>
        </div>
        <div class="px-4">
            <i class="fa-solid fa-caret-down icon-blue"></i>
        </div>
    </div>
</template>

<script>
export default {
    name: 'PreparationCard',
    props: {
        icon: String,
        title: String
    }
}
</script>

<style>
.card-preparation {
    border-radius: 10px;
    border: 0.5px #F4F6FB solid;
}
.reason-title {
    margin: 0;
}
</style>