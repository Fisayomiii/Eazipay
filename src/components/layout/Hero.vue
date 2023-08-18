<template>
    <div class="herobg flex min-h-screen bg-white pb-20">
        <div class="flex flex-col justify-center flex-1 px-8 py-8 md:px-12 lg:flex-none lg:px-24">
            <div class="w-full mx-auto lg:max-w-6xl">
                <div class="max-w-xl mx-auto text-center lg:p-10 lg:text-left">
                    <div>
                        <p class="text-5xl font-medium font-semibold text-black sm:text-5xl">
                            Run your <span class="text-[#11453B]">payroll</span> <br>
                            <span class="text-[#B4A572]"> easily</span> in <span class="text-[#EA4E4B]">seconds</span>
                        </p>
                        <p class="max-w-xl mt-4 text-lg tracking-tight text-gray-600">
                            We’ve built an all-inclusive simple solution for individual and businesses to manage staff, pay
                            salaries, bills, and relevant taxes all at once.
                        </p>
                    </div>
                    <div
                        class="flex flex-col items-center justify-center max-w-lg gap-3 mx-auto mt-10 lg:flex-row lg:justify-start">
                        <a href="#"
                            class="items-center justify-center w-full px-6 py-2.5 text-center text-white duration-200 bg-[#11453b] border-2 border-[#11453B] rounded-full inline-flex hover:bg-transparent hover:border-[#11453B] hover:text-black focus:outline-none lg:w-auto focus-visible:outline-black text-sm focus-visible:ring-black">
                            Start Using Free, Forever
                        </a>
                    </div>
                    <div class="mt-8 lg:mt-12">
                        <p class="mb-4 text-black font-medium"> Download the Eazipay App </p>
                        <div class="inline-flex gap-4">
                            <a target="_blank" rel="noopener noreferrer"
                                href="https://play.google.com/store/apps/details?id=com.myeazipay.business"
                                class="inline-block">
                                <img data-v-4bf142b6 src="../../assets/imgs/google-store.af961bc5.png">
                            </a>
                            <a target="_blank" rel="noopener noreferrer"
                                href="https://apps.apple.com/us/app/eazipay-business/id6446281426" class="inline-block">
                                <img data-v-4bf142b6 src="../../assets/imgs/apple-store.1c73f0ba.png">
                            </a>
                        </div>
                    </div>
                </div>
            </div>
        </div>
        <div class="relative flex-1 hidden w-0 lg:block">
            <div>
                <img class="absolute inset-0 object-cover w-full h-full"
                    src="../../assets/imgs/hero-media-desktop.5f900d38.png" alt="hero-media-desktop">
            </div>
        </div>
    </div>
</template>
<style scoped>
.herobg {
    /* background-color: #E5E7EB; */
    background-image: url('../../assets/imgs/gradients.fdc2f6b1.png');
    background-position: 50% 60%, 0px 0px;
    background-size: cover, auto;
    background-repeat: no-repeat;
}

img[data-v-4bf142b6] {
    height: 66px;
}

img[data-v-4bf142b6] {
    box-shadow: 0 20px 48px 0 hsla(0, 0%, 66.7%, .29);
    border-radius: 9px;
    height: 60px;
}
</style>