<template>

</template>

<script>
import Ccard from "@/component/Ccard.vue";
import ProjectCard from "@/component/ProjectCard.vue";
export default {
    name: "CodedApp",
    components: { ProjectCard, Ccard},
    data() {
        return {
            form: {
                email: null,
                subject: null,
                message: null
            }
        }
    },
    methods: {
        submit() {
            axios.post('/contact-us', this.form)
                .finally(_ =>
                    this.form = {
                        email: null,
                        subject: null,
                        message: null
                    })
        }
    }
}
</script>

<style scoped>

</style>
