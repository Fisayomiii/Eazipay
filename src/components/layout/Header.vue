<template>
    <div class="w-full mx-auto 2xl:max-w-7xl">
        <div
            class="relative flex flex-col w-full p-5 mx-auto bg-white md:items-center md:justify-between md:flex-row md:px-6 lg:px-8">
            <div class="flex flex-row items-center justify-between lg:justify-start">
                <a class="text-lg tracking-tight text-black uppercase focus:outline-none focus:ring lg:text-2xl" href="/">
                    <img src="../../assets/imgs/eazipaylogo.png" alt="" class="h-6">
                </a>
                <button class="block md:hidden navbar-burger flex items-center text-[#17493F] p-3"
                    @click="showMenu = !showMenu">
                    <svg class="block h-4 w-4 fill-current" viewBox="0 0 20 20" xmlns="http://www.w3.org/2000/svg">
                        <title>Mobile menu</title>
                        <path d="M0 3h20v2H0V3zm0 6h20v2H0V9zm0 6h20v2H0v-2z"></path>
                    </svg>
                </button>
            </div>
            <nav class="flex-col items-center flex-grow hidden md:pb-0 md:flex md:justify-end md:flex-row">
                <a class="px-2 py-2 text-sm text-gray-500 lg:px-6 md:px-3 hover:text-[#11453B] lg:ml-auto transition duration-200 transition ease-in-out delay-150  duration-300"
                    href="#">
                    Individual
                </a>
                <a class="px-2 py-2 text-sm text-gray-500 lg:px-6 md:px-3 hover:text-[#11453B] transition duration-200 transition ease-in-out delay-150  duration-300"
                    href="#">
                    Pricing
                </a>
                <a class="px-2 py-2 text-sm text-gray-500 lg:px-6 md:px-3 hover:text-[#11453B] transition duration-200 transition ease-in-out delay-150  duration-300"
                    href="#">
                    Business
                </a>
                <a class="px-2 py-2 text-sm text-gray-500 lg:px-6 md:px-3 hover:text-[#11453B] transition duration-200 transition ease-in-out delay-150  duration-300"
                    href="#">
                    Set your Payroll
                </a>

                <div class="inline-flex items-center gap-2 list-none lg:ml-auto">
                    <button
                        class="block px-5 py-2 mt-2 text-sm text-gray-500 md:mt-0 rounded-full border-0 ring-2 ring-inset ring-[#11453B] transition duration-200 transition ease-in-out delay-150  duration-300 active:bg-[#11453B] focus:outline-none focus:ring focus:ring-[#11453B] hover:text-[#11453B]">
                        Log in
                    </button>
                    <button
                        class="inline-flex items-center justify-center px-4 py-2 text-sm font-semibold text-white bg-[#11453B] rounded-full group transition duration-200 transition ease-in-out delay-150  duration-300 focus:outline-none focus-visible:outline-2 focus-visible:outline-offset-2 hover:bg-[#2A5D54] active:bg-gray-800 active:text-white focus-visible:outline-black">
                        Register
                    </button>
                </div>
            </nav>

            <div class="relative z-50" :class="showMenu ? 'flex' : 'hidden'">
                <div class="inset-0 fixed bg-gray-800 opacity-25"></div>
                <nav
                    class="fixed top-0 right-0 bottom-0 flex flex-col w-5/6 max-w-sm py-6 px-5 bg-white border-r overflow-y-auto">
                    <div class="flex items-center mb-8">
                        <button @click="showMenu = !showMenu">
                            <svg class="h-6 w-6 text-[#17493F] cursor-pointer hover:text-[#17493F]"
                                xmlns="http://www.w3.org/2000/svg" fill="none" viewBox="0 0 24 24" stroke="currentColor">
                                <path stroke-linecap="round" stroke-linejoin="round" stroke-width="2"
                                    d="M6 18L18 6M6 6l12 12">
                                </path>
                            </svg>
                        </button>

                        <a class="text-3xl ml-3 font-bold leading-none" href="/">
                            <img src="../../assets/imgs/eazipaylogo.png" class="h-8" alt="">
                        </a>
                    </div>

                    <div>
                        <ul>
                            <li class="mb-1" v-motion-slide-visible-once-bottom>
                                <a class="block p-4 text-sm font-semibold text-gray-900 hover:text-[#11453B] hover:text-[#17493F] rounded"
                                    href="/">Individual</a>
                            </li>
                            <li class="mb-1" v-motion-slide-visible-once-bottom>
                                <a class="block p-4 text-sm font-semibold text-gray-900 hover:text-[#11453B] hover:text-[#17493F] rounded"
                                    href="/">Pricing</a>
                            </li>
                            <li class="mb-1" v-motion-slide-visible-once-bottom>
                                <a class="block p-4 text-sm font-semibold text-gray-900 hover:text-[#11453B] hover:text-[#17493F] rounded"
                                    href="/">Business</a>
                            </li>
                            <li class="mb-1" v-motion-slide-visible-once-bottom>
                                <a class="block p-4 text-sm font-semibold text-gray-900 hover:text-[#11453B] hover:text-[#17493F] rounded"
                                    href="/">Set your Payroll</a>
                            </li>
                        </ul>
                    </div>
                    <div class="mt-auto">
                        <div class="pt-6">
                            <a class="block px-4 py-4 mb-3 leading-loose text-xs text-center font-semibold leading-none border-0 ring-2 ring-inset ring-[#11453B] active:bg-[#11453B] focus:outline-none focus:ring focus:ring-[#11453B] transition duration-200 transition ease-in-out delay-150  duration-300 rounded-full"
                                href="/" v-motion-pop-visible-once>Log in</a>
                            <a class="block px-4 py-3 mb-2 leading-loose text-white text-xs text-center font-semibold bg-[#11453B] hover:bg-[#11453B] active:bg-[#11453B] focus:outline-none focus:ring focus:ring-[#11453B] font-bold rounded-full transition duration-200 transition ease-in-out delay-150  duration-300"
                                href="/" v-motion-pop-visible-once>Sign Up</a>
                        </div>
                    </div>
                </nav>
            </div>
        </div>
    </div>
</template>


<script>
import { Power3, gsap } from 'gsap/all';
export default {
    data() {
        return {
            showMenu: false,
        };
    },
    mounted() {
        this.startAnimation();
    },
    methods: {
        startAnimation() {
            gsap.fromTo(
                this.$refs.head, // Target element
                { opacity: 0, y: -60 }, // From properties
                { opacity: 1, y: 0, duration: 1, ease: Power3.easeOut, delay: 1.8 }
            );
        },
    },
};
</script>