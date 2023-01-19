<template>

    <div class="bg-primary" style="border-radius: 0 0 300px 0">
        <div class="h-10 pt-6 px-6">
            <nav class="border-gray-200 px-4 lg:px-6 py-2.5 text-white">
                <div class="flex flex-wrap justify-between items-center mx-auto max-w-screen-xl">
                    <a href="#" class="flex items-center">
                        <span class="self-center text-2xl  font-bold whitespace-nowrap text-white hidden lg:flex">codedAcademy</span>
                    </a>
                    <h1 class=" font-bold text-3xl lg:hidden">codedAcademy</h1>
                    <div class="flex items-center lg:order-2">
                        <a href="#"
                           class="hidden md:visible  text-gray-800 dark:text-white hover:bg-gray-50 focus:ring-4 focus:ring-gray-300 font-medium rounded-lg text-sm px-4 lg:px-5 py-2 lg:py-2.5 mr-2 dark:hover:bg-gray-700 focus:outline-none dark:focus:ring-gray-800">Log
                            in</a>
                        <a href="#"
                           class="hidden md:visible text-white bg-primary-700 hover:bg-primary-800 focus:ring-4 focus:ring-primary-300 font-medium rounded-lg text-sm px-4 lg:px-5 py-2 lg:py-2.5 mr-2 dark:bg-primary-600 dark:hover:bg-primary-700 focus:outline-none dark:focus:ring-primary-800">Get
                            started</a>
                        <button @click="mobileMenu  = true" type="button"
                                class="inline-flex items-center p-2 ml-1 text-sm text-gray-500 rounded-lg hidden hover:bg-gray-100 focus:outline-none focus:ring-2 focus:ring-gray-200 dark:text-gray-400 dark:hover:bg-gray-700 dark:focus:ring-gray-600"
                                aria-controls="mobile-menu-2" aria-expanded="false">
                            <span class="sr-only">Open main menu</span>
                            <svg class="w-6 h-6" fill="currentColor" viewBox="0 0 20 20"
                                 xmlns="http://www.w3.org/2000/svg">
                                <path fill-rule="evenodd"
                                      d="M3 5a1 1 0 011-1h12a1 1 0 110 2H4a1 1 0 01-1-1zM3 10a1 1 0 011-1h12a1 1 0 110 2H4a1 1 0 01-1-1zM3 15a1 1 0 011-1h12a1 1 0 110 2H4a1 1 0 01-1-1z"
                                      clip-rule="evenodd"></path>
                            </svg>
                            <svg class="hidden w-6 h-6" fill="currentColor" viewBox="0 0 20 20"
                                 xmlns="http://www.w3.org/2000/svg">
                                <path fill-rule="evenodd"
                                      d="M4.293 4.293a1 1 0 011.414 0L10 8.586l4.293-4.293a1 1 0 111.414 1.414L11.414 10l4.293 4.293a1 1 0 01-1.414 1.414L10 11.414l-4.293 4.293a1 1 0 01-1.414-1.414L8.586 10 4.293 5.707a1 1 0 010-1.414z"
                                      clip-rule="evenodd"></path>
                            </svg>
                        </button>
                    </div>
                    <div class="hidden justify-between items-center w-full lg:flex lg:w-auto lg:order-1"
                         id="mobile-menu-2">
                        <ul class="flex flex-col mt-4 font-medium lg:flex-row lg:space-x-8 lg:mt-0">
                            <li>
                                <a href="#"
                                   class="block py-2 pr-4 pl-3 text-white rounded bg-primary-700 lg:bg-transparent lg:text-primary-700 lg:p-0 dark:text-white"
                                   aria-current="page">Courses</a>
                            </li>
                            <li>
                                <a href="#"
                                   class="block py-2 pr-4 pl-3 text-gray-700 border-b border-gray-100 hover:bg-gray-50 lg:hover:bg-transparent lg:border-0 lg:hover:text-primary-700 lg:p-0 dark:text-gray-400 lg:dark:hover:text-white dark:hover:bg-gray-700 dark:hover:text-white lg:dark:hover:bg-transparent dark:border-gray-700">Pricing</a>
                            </li>
                            <li>
                                <a href="#"
                                   class="block py-2 pr-4 pl-3 text-gray-700 border-b border-gray-100 hover:bg-gray-50 lg:hover:bg-transparent lg:border-0 lg:hover:text-primary-700 lg:p-0 dark:text-gray-400 lg:dark:hover:text-white dark:hover:bg-gray-700 dark:hover:text-white lg:dark:hover:bg-transparent dark:border-gray-700">About
                                    Us</a>
                            </li>
                            <li>
                                <a href="#"
                                   class="block py-2 pr-4 pl-3 text-gray-700 border-b border-gray-100 hover:bg-gray-50 lg:hover:bg-transparent lg:border-0 lg:hover:text-primary-700 lg:p-0 dark:text-gray-400 lg:dark:hover:text-white dark:hover:bg-gray-700 dark:hover:text-white lg:dark:hover:bg-transparent dark:border-gray-700">Contact
                                    Us</a>
                            </li>
                        </ul>
                    </div>
                </div>
            </nav>
        </div>

        <div class="flex text-white grid lg:grid-cols-2 grid-cols-1 md:py-0 ">
            <div class="mx-auto justify-center my-auto px-24 pt-24 lg:py-0">
                <h1 class="font-bold md:text-4xl text-2xl lg:text-6xl">Upgrade YOUR skills for better future</h1>
                <p class="pt-10">Lorem ipsum dolor sit amet consectetur. Erat in commodo in a. Sit interdum mi felis
                    laoreet sagittis.</p>
                <div class="pt-12 space-x-8 grid grid-cols-1 md grid-cols-2">
                    <button class="text-white bg-pink-400 rounded-xl text-sm py-2 px-4">Check Courses</button>
                    <button class="bg-transparent border-2 rounded-xl text-sm">Learn more</button>
                </div>
            </div>
            <div class="lg:py-12 mx-auto lg:mx-0">
                <img class="md:px-4 py-12 pb-36 md:ml-12" src="/images/banner2.svg">
            </div>
        </div>
    </div>

    <!--    Our Courses Section-->

    <div class="px-24 pb-20">
        <h1 class=" w-full text-4xl font-bold py-8 ">Our Courses</h1>
        <div class="grid grid-cols-1 md:grid-cols-2 lg:grid-cols-4 gap-6">
            <!--            Card 1-->
            <div
                class="bg-white shadow-md rounded-xl p-5 transform hover:translate-y-2 hover:shadow-xl transition duration-300">
                <img
                    src="https://srv-cdn.onedio.com/store/988bccbdb9ca395f581f98faa9ce3a55123f12bfcef608c838532b813646e557.png"
                    alt="Mobile" class="mx-auto mb-3"/>
                <div class="bg-gray-700 text-white p-5 rounded-xl">
                    <h2 class="text-xl font-bold">iPhone XR</h2>
                    <div class="flex py-2 gap-x-2 h-8">
                        <img src="/images/i-star.svg">
                        <img src="/images/i-star.svg">
                        <img src="/images/i-star.svg">
                        <img src="/images/i-star.svg">
                        <img src="/images/i-star.svg">
                    </div>
                    <h1 class="text-xl">$599,00</h1>
                </div>
            </div>
            <!--                Card 1 End-->
            <!--            Card 1-->
            <div
                class="bg-white shadow-md rounded-xl p-5 transform hover:translate-y-2 hover:shadow-xl transition duration-300">
                <img
                    src="https://srv-cdn.onedio.com/store/988bccbdb9ca395f581f98faa9ce3a55123f12bfcef608c838532b813646e557.png"
                    alt="Mobile" class="mx-auto mb-3"/>
                <div class="bg-gray-700 text-white p-5 rounded-xl">
                    <h2 class="text-xl font-bold">iPhone XR</h2>
                    <div class="flex py-2 gap-x-2 h-8">
                        <img src="/images/i-star.svg">
                        <img src="/images/i-star.svg">
                        <img src="/images/i-star.svg">
                        <img src="/images/i-star.svg">
                        <img src="/images/i-star.svg">
                    </div>
                    <h1 class="text-xl">$599,00</h1>
                </div>
            </div>
            <!--                Card 1 End-->
            <!--            Card 1-->
            <div
                class="bg-white shadow-md rounded-xl p-5 transform hover:translate-y-2 hover:shadow-xl transition duration-300">
                <img
                    src="https://srv-cdn.onedio.com/store/988bccbdb9ca395f581f98faa9ce3a55123f12bfcef608c838532b813646e557.png"
                    alt="Mobile" class="mx-auto mb-3"/>
                <div class="bg-gray-700 text-white p-5 rounded-xl">
                    <h2 class="text-xl font-bold">iPhone XR</h2>
                    <div class="flex py-2 gap-x-2 h-8">
                        <img src="/images/i-star.svg">
                        <img src="/images/i-star.svg">
                        <img src="/images/i-star.svg">
                        <img src="/images/i-star.svg">
                        <img src="/images/i-star.svg">
                    </div>
                    <h1 class="text-xl">$599,00</h1>
                </div>
            </div>
            <!--                Card 1 End-->
            <!--            Card 1-->
            <div
                class="bg-white shadow-md rounded-xl p-5 transform hover:translate-y-2 hover:shadow-xl transition duration-300">
                <img
                    src="https://srv-cdn.onedio.com/store/988bccbdb9ca395f581f98faa9ce3a55123f12bfcef608c838532b813646e557.png"
                    alt="Mobile" class="mx-auto mb-3"/>
                <div class="bg-gray-700 text-white p-5 rounded-xl">
                    <h2 class="text-xl font-bold">iPhone XR</h2>
                    <div class="flex py-2 gap-x-2 h-8">
                        <img src="/images/i-star.svg">
                        <img src="/images/i-star.svg">
                        <img src="/images/i-star.svg">
                        <img src="/images/i-star.svg">
                        <img src="/images/i-star.svg">
                    </div>
                    <h1 class="text-xl">$599,00</h1>
                </div>
            </div>
            <!--                Card 1 End-->
        </div>
    </div>
    <!--    Our Courses Section-->



    <div class="px-24">
        <h1 class="text-center text-4xl font-bold">Our Features and Services</h1>
        <p class=" w-1/2 text-center mx-auto pt-6">Lorem ipsum dolor sit amet consectetur. Erat in commodo in a. Sit interdum mi felis
            laoreet sagittis.Lorem ipsum dolor sit amet consectetur.</p>
    </div>

    <!--    Our Feature-->
    <div class="px-48 justify-items-center flex grid grid-cols-1 md:grid-cols-2 lg:grid-cols-3">
        <div class="w-56 pt-16">
            <div class="py-3">
                <img class="h-9" src="image/i-key.svg">
            </div>
            <h1 class="font-bold py-2 text-xl">Life Time Access</h1>
            <p>Lorem ipsum dolor sit amet consectetur. Erat in commodo in a.</p>
        </div>
        <div class="w-56 pt-16">
            <div class="py-3">
                <img class="h-9" src="image/i-monitor.svg">
            </div>
            <h1 class="font-bold py-2 text-xl">Online Classes</h1>
            <p>Lorem ipsum dolor sit amet consectetur. Erat in commodo in a.</p>
        </div>
        <div class="w-56 pt-16">
            <div class="py-3">
                <img class="h-9" src="image/i-certificate.svg">
            </div>
            <h1 class="font-bold py-2 text-xl">Get Certificate</h1>
            <p>Lorem ipsum dolor sit amet consectetur. Erat in commodo in a.</p>
        </div>
        <div class="w-56 pt-16">
            <div class="py-3">
                <img class="h-9" src="image/i-user.svg">
            </div>
            <h1 class="font-bold py-2 text-xl">Expert Trainers</h1>
            <p>Lorem ipsum dolor sit amet consectetur. Erat in commodo in a.</p>
        </div>
        <div class="w-56 pt-16">
            <div class="py-3">
                <img class="h-9" src="image/i-badge_check.svg">
            </div>
            <h1 class="font-bold py-2 text-xl">Great Result</h1>
            <p>Lorem ipsum dolor sit amet consectetur. Erat in commodo in a.</p>
        </div>
        <div class="w-56 pt-16">
            <div class="py-3">
                <img class="h-9" src="image/i-badge_dollar.svg">
            </div>
            <h1 class="font-bold py-2 text-xl">Best Price</h1>
            <p>Lorem ipsum dolor sit amet consectetur. Erat in commodo in a.</p>
        </div>
    </div>
    <!--    Our Feature-->


    <div class="lg:px-56 flex md:pt-32 pt-16 grid grid-cols-1 md:grid-cols-2">
        <div class="flex-none mx-auto">
            <img class="md:h-96 h-72" src="image/platform.png">
        </div>

        <div class="lg:pl-20 md:pl-0 px-20 mx-auto my-auto pt-8 md:pt-0">
            <h1 class="text-4xl font-bold py-4">Best Platform to grow</h1>
            <p class="pb-4">Lorem ipsum dolor sit amet consectetur. Erat in commodo in a. Sit interdum mi felis
                laoreet sagittis.Lorem ipsum dolor sit amet consectetur.Erat in commodo in a. Sit interdum mi felis
                laoreet sagittis.Lorem ipsum dolor sit amet consectetur.</p>

            <button class="text-white bg-pink-400 rounded-xl text-sm py-2 px-4">Check Courses</button>
        </div>

    </div>
    <div class="lg:px-56 flex md:pt-32 pt-16 grid grid-cols-1 md:grid-cols-2">
        <div class="pl-20 my-auto pt-8 md:pt-0">
            <h1 class="text-4xl font-bold py-4">24/7 Students Support</h1>
            <p class="pb-4">Lorem ipsum dolor sit amet consectetur. Erat in commodo in a. Sit interdum mi felis
                laoreet sagittis.Lorem ipsum dolor sit amet consectetur.Erat in commodo in a. Sit interdum mi felis
                laoreet sagittis.Lorem ipsum dolor sit amet consectetur.</p>

            <button class="text-white bg-violet-800 rounded-xl text-sm py-2 px-7">Read More</button>
        </div>

        <div class="flex-none mx-auto">
            <img class="md:h-96 h-72" src="image/student_support.png">
        </div>

    </div>

    <div class="bg-violet-900 py-16 px-16 mt-10">
        <div class="bg-white rounded-3xl  flex pt-16 grid grid-cols-1 md:grid-cols-2">
            <div class="flex-none mx-auto">
                <img class="md:h-96 h-72" src="image/email.svg">
            </div>

            <div class="md:pt-16 pr-16 px-28 md:px-0">
                <h1 class="text-3xl font-bold py-4">Subscribe to our newsletter</h1>
                <p class="pb-4">Lorem ipsum dolor sit amet consectetur. Erat in commodo in a. Sit interdum mi felis
                    laoreet sagittis.Lorem ipsum dolor sit amet consectetur.</p>

                <!--                <div class="pb-10">-->
                <!--                    <form class="flex">-->
                <!--                        <input class="rounded-l-lg py-2 px-4 border-t mr-0 border-b border-l text-gray-800 border-gray-200 bg-white" placeholder="Enter your email"/>-->
                <!--                        <button class="px-8 py-2 rounded-lg bg-violet-800 text-white font-bold p-4 uppercase border-yellow-500 border-t border-b border-r">Join Now</button>-->
                <!--                    </form>-->
                <!--                </div>-->
            </div>

        </div>
    </div>


</template>

<script>
export default {
    name: "CodedAcademy"
}
</script>

<style scoped>

</style>
