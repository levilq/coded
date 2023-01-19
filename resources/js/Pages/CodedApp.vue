<template>
    <div class="10/12">
        <!--        Greeting Card-->
        <div class="py-20">
            <div class="c-gradient w-10/12 md:w-2/5 mx-auto rounded-xl ">
                <!-- Explanation in JS tab -->



                <div class="flex">
                    <h1 class="font-bold px-4 text-2xl md:text-5xl">It's</h1>
                    <img class="w-32 md:w-40" src="images/coded-logo.svg">
                </div>

                <p class="text-sm px-4 py-2 md:py-6">Our experienced team is ready to develop a project of any complexity
                    for you or integrate our ready-made
                    solutions into your project</p>

                <div class="flex w-80 gap-6 px-4 py-4 md:pb-4">
                    <a href="#">
                        <img src="images/social-facebook.svg" title="Facebook">
                    </a>
                    <a href="#">
                        <img src="images/social-instagram.svg" title="Instagram">
                    </a>
                    <a href="#">
                        <img src="images/social-linkedin.svg" title="LikedIn">
                    </a>
                    <a href="#">
                        <img src="images/social-twitter.svg" title="Twitter">
                    </a>
                </div>
            </div>
        </div>
        <!--        End Greeting Card-->

        <!--    About Us Container-->
        <ccard class="w-10/12 flex">
            <div class="py-5 flex gap-y-5 lg:px-32 md:gap-x-36 mx-auto grid grid-cols-1 lg:grid-cols-3 lg:py-6">
                <div class="mx-auto">
                    <div class="flex">
                        <img class="" src="images/i-bag.png">
                        <h1 class="text-7xl mt-3">15</h1>
                    </div>
                    <h1 class="text-2xl font-bold">Completed Project</h1>
                </div>
                <div class="mx-auto">
                    <div class="flex">
                        <img class="pt-4 pr-3" src="images/i-clock.png">
                        <h1 class="text-7xl">4534</h1>
                    </div>
                    <h1 class="text-2xl font-bold pt-4 ml-10 md:mx-auto">Working Hours</h1>
                </div>
                <div class="mx-auto">
                    <div class="flex">
                        <img class="pt-4" src="images/i-heart.png">
                        <h1 class="text-7xl">40</h1>
                    </div>
                    <h1 class="text-2xl font-bold pt-4">Happy Clients</h1>
                </div>
            </div>
        </ccard>
        <!--    End About Us Container-->

        <!--    Our work section-->
        <div class="w-10/12 mx-auto pt-24">
            <div>
                <h1 class="font-bold text-4xl py-6 mx-auto flex">Our Work</h1>
                <p class="w-10/12 pb-6">We are a few years old, but we already have something to brag about</p>
            </div>

            <div class="flex mx-auto grid grid-cols-1 lg:grid-cols-4 gap-y-8 md:gap-x-8 ">
                <project-card>
                    <a href="www.echo.tj">
                        <div class="px-5 py-3">
                            <img class="w-12" src="images/echo-logo.png">
                            <h1 class="text-primary font-bold text-xl py-3">Echo.</h1>
                            <p class="w-4/5">Music portal "Echo of Tajikistan"</p>
                        </div>
                    </a>
                </project-card>
                <project-card>
                    <a href="#">
                        <div class="px-5 py-3">
                            <img class="w-6" src="images/akf-logo.png">
                            <h1 class="text-primary font-bold text-xl py-3">E-library.</h1>
                            <p class="w-4/5">Interactive electronic library</p>
                        </div>
                    </a>
                </project-card>
                <project-card>
                    <a href="#">
                        <div class="px-5 py-3">
                            <img class="w-6" src="images/akf-logo.png">
                            <h1 class="text-primary font-bold text-xl py-3">LMS</h1>
                            <p class="w-4/5">Education automation system</p>
                        </div>
                    </a>
                </project-card>
                <project-card>
                    <a href="#">
                        <div class="px-5 py-3">
                            <img class="w-16" src="images/schools2030-logo.png">
                            <h1 class="text-primary font-bold text-xl py-3">Schools2030</h1>
                            <p class="w-48">Schools2030 is a programme of the Aga Khan Foundation</p>
                        </div>
                    </a>
                </project-card>
            </div>


            <div class="py-20">
                <div class="font-bold text-4xl py-6 mx-auto flex">
                    <h1>Ready Made</h1>
                </div>

                <div class="grid grid-cols-1 lg:grid-cols-3  gap-y-5 md:gap-x-8">
                    <ccard>
                        <a href="mailto:sultonazar@outlook.com">
                            <div class="py-6 px-4">
                                <lord-icon
                                    src="https://cdn.lordicon.com/wlpxtupd.json"
                                    trigger="loop"
                                    delay="2000"
                                    colors="primary:#02c4f9,secondary:#f8016a"
                                    style="width:60px;height:60px">
                                </lord-icon>
                                <h3 class="font-bold py-3 text-lg">C-Logistics</h3>
                                <p>C-Logistics will allow you and your customers to calculate the cost and track goods in
                                    real
                                    time.</p>
                            </div>
                        </a>
                    </ccard>
                    <ccard>
                        <a href="mailto:sultonazar@outlook.com">
                            <div class="py-6 px-4">
                                <lord-icon
                                    src="https://cdn.lordicon.com/rqqkvjqf.json"
                                    trigger="loop"
                                    delay="2000"
                                    colors="primary:#02c4f9,secondary:#f8016a"
                                    style="width:60px;height:60px">
                                </lord-icon>
                                <h3 class="font-bold py-3 text-lg">C-Bio</h3>
                                <p>Add biometric authorization and authentication to your web, windows or android
                                    application.</p>
                            </div>
                        </a>
                    </ccard>
                    <ccard>
                        <a href="mailto:sultonazar@outlook.com">
                            <div class="py-6 px-4">
                                <lord-icon
                                    src="https://cdn.lordicon.com/fpipqhrr.json"
                                    trigger="loop"
                                    delay="2000"
                                    colors="primary:#02c4f9,secondary:#f8016a"
                                    style="width:60px;height:60px">
                                </lord-icon>
                                <h3 class="font-bold py-3 text-lg">C-Music</h3>
                                <p>A modern music engine for your web application will allow you to develop modern musical
                                    platform.</p>
                            </div>
                        </a>
                    </ccard>


                </div>
                <div class="grid grid-cols-1 lg:grid-cols-3  gap-y-5 md:gap-x-8 pt-6">
                    <ccard>
                        <a href="mailto:sultonazar@outlook.com">
                            <div class="py-6 px-4">
                                <lord-icon
                                    src="https://cdn.lordicon.com/nocovwne.json"
                                    trigger="loop"
                                    delay="2000"
                                    colors="primary:#02c4f9,secondary:#f8016a"
                                    style="width:60px;height:60px">
                                </lord-icon>
                                <h3 class="font-bold py-3 text-lg">C-Blog</h3>
                                <p>C-Blog is complete module for your personal blog or web application. It will make the
                                    discussion easier in your application.</p>
                            </div>
                        </a>
                    </ccard>
                    <ccard>
                        <a href="mailto:sultonazar@outlook.com">
                            <div class="py-6 px-4">
                                <lord-icon
                                    src="https://cdn.lordicon.com/huwchbks.json"
                                    trigger="loop"
                                    delay="2000"
                                    colors="primary:#02c4f9,secondary:#f8016a"
                                    style="width:70px;height:70px">
                                </lord-icon>
                                <h3 class="font-bold py-3 text-lg">C-Till</h3>
                                <p>C-Till will allow
                                    you to make payments in different currencies. We will help you integrate the cash
                                    register module into your project</p>
                            </div>
                        </a>
                    </ccard>
                    <ccard>
                        <a href="mailto:sultonazar@outlook.com">
                            <div class="py-6 px-4">
                                <lord-icon
                                    src="https://cdn.lordicon.com/fgkmrslx.json"
                                    trigger="loop"
                                    delay="2000"
                                    colors="primary:#02c4f9,secondary:#f8016a"
                                    style="width:60px;height:60px">
                                </lord-icon>
                                <h3 class="font-bold py-3 text-lg">C-Gallery</h3>
                                <p>C-Gallery will allow your web app to easily manage photo and video albums. Image caching
                                    and sizing mechanism will speed up page loading, and the duplicate search function will
                                    remove unnecessary</p>
                            </div>
                        </a>
                    </ccard>

                </div>
            </div>
        </div>
        <!--    End Our work section-->


        <!--    Start upcoming work section-->
        <div class="pb-12">
            <div class="w-10/12 mx-auto">
                <h1 class="font-bold text-4xl py-6 mx-auto flex">Upcomig Projects</h1>
                <p class="w-10/12 pb-6">Soon you will see our new project</p>
            </div>
            <div class="c-gradient shadow rounded-md p-4 w-10/12 mx-auto">
                <div class="animate-pulse flex space-x-4 py-6">
                    <div class="rounded-full bg-slate-700 h-10 w-10"></div>
                    <div class="flex-1 space-y-6 py-1">
                        <div class="h-2 bg-slate-700 rounded"></div>
                        <div class="space-y-3">
                            <div class="grid grid-cols-3 gap-4">
                                <div class="h-2 bg-slate-700 rounded col-span-2"></div>
                                <div class="h-2 bg-slate-700 rounded col-span-1"></div>
                            </div>
                            <div class="h-2 bg-slate-700 rounded"></div>
                        </div>
                    </div>
                </div>
            </div>
        </div>

        <!--    End upcoming work section-->


        <div class="w-10/12 mx-auto text-center">
            <h1 class="font-bold text-4xl py-6 ">Lets Work Together</h1>
        </div>

        <div class="flex mx-auto w-10/12 gap-8 grid grid-cols-1 lg:grid-cols-2">
            <div class="md:pr-52 md:pl-16">
                <img class="w-56 md:w-96 mx-auto md:ml-28 md:p-0" src="images/coded-logo.svg">

                <div class="flex gap-x-8 pl-9 py-12 md:ml-36 w-10/12">
                    <a href="#">
                        <img src="images/i-f-facebook.svg">
                    </a>
                    <a href="#">
                        <img src="images/i-f-linkedin.svg">
                    </a>
                    <a href="#">
                        <img src="images/i-f-twitter.svg">
                    </a>
                    <a href="#">
                        <img src="images/i-f-instagram.svg">
                    </a>
                </div>

                <div class=" text-center md:ml-36 md:text-2xl">
                    <h1>Say hello, on Email</h1>
                    <h1>info@coded.com</h1>
                </div>

            </div>

            <div class="bg-cprimary flex w-full grid grid-cols-1 lg:grid-cols-2">
                <div class="p-10 text-6xl font-bold md:pt-16">
                    <h1>Contact</h1>
                    <h1 class="text-primary">Us</h1>
                </div>
                <div class="w-full">
                    <section class="bg-cprimary ">
                        <div class="py-8 lg:py-16 px-4 mx-auto max-w-screen-md">
                            <form @submit.prevent.capture="submit" class="space-y-8">
                                <div>
                                    <label for="email"
                                           class="block mb-2 text-sm font-medium text-gray-300">Your
                                        email</label>
                                    <input type="email" name="email"
                                           v-model="form.email"
                                           class="shadow-sm bg-transparent border border-gray-300 text-white text-sm rounded-lg focus:ring-primary-500 focus:border-primary-50 block w-full p-2.5"
                                           placeholder="name@coded.com" required>
                                </div>
                                <div>
                                    <label for="subject"
                                           class="block mb-2 text-sm font-medium text-gray-300">Subject</label>
                                    <input type="text" name="subject"
                                           v-model="form.subject"
                                           class="block p-3 w-full text-sm text-white bg-transparent rounded-lg border border-gray-300 shadow-sm focus:ring-primary-500 focus:border-primary-500"
                                           placeholder="Let us know how we can help you" required>
                                </div>
                                <div class="sm:col-span-2">
                                    <label for="message"
                                           class="block mb-2 text-sm font-medium text-gray-300">Your
                                        message</label>
                                    <textarea name="message" rows="6"
                                              v-model="form.message"
                                              class="block p-2.5 w-full text-sm text-white bg-transparent rounded-lg shadow-sm border border-gray-300 focus:ring-primary-500 focus:border-primary-500"
                                              placeholder="Leave a comment..."></textarea>
                                </div>
                                <button type="submit"
                                        class="c-gradient py-3 px-5 text-sm font-medium text-center text-white rounded-lg sm:w-fit focus:ring-4 focus:outline-none focus:ring-primary-300">
                                    Send message
                                </button>
                            </form>
                        </div>
                    </section>
                </div>
            </div>
        </div>



        <div class="w-10/12 mx-auto text-center py-20 text-primary font-bold">
            <h1 class="text-5xl">
                CREATIVETY ABOVE
            </h1>
        </div>




    </div>
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
