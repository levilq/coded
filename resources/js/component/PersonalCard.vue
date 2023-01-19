<template>
    <div class="personal-card">
        <div class="content grid gap-y-4">
            <img class="rounded-full mx-auto" :src="avatar">
            <h4 class="text-primary text-lg text-center font-extrabold">{{title}}</h4>
            <p class="text-black text-center">
                <slot></slot>
            </p>
        </div>
    </div>
</template>

<script>
export default {
    name: "PersonalCard",
    props:{
        avatar:String,
        title:String

    }
}
</script>

<style scoped>

</style>
