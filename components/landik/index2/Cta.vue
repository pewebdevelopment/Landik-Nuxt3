<template>
    <section class="py-20 bg-white relative">
        <div class="container">
            <div class="grid grid-cols-1">
                <div class="rounded-2xl py-[60px] px-[30px] bg-custom relative before:bg-no-repeat before:bg-cover before:absolute before:bg-[url('/assets/images/counter_bg.png')] before:left-0 before:bottom-0 before:w-full before:h-[120px]">
                    <div class="relative text-white text-center">
                        <h2 class="font-bold text-[32px] md:text-[40px] capitalize z-10">People Using Our Software &amp; Counting</h2>
                        <p class="mx-auto mt-6 max-w-[600px] text-lg">Due to its widespread use as filler text for layouts, non-readability is of great importance.</p>
                    </div>
                    <div class="text-center mt-12 relative">
                        <h1 class="font-bold text-white tracking-[7px] text-[46px] md:text-[80px]" data-vanilla-counter 
                        data-start-at="194468" 
                        data-end-at="195468" 
                        data-time="2"
                        data-delay="900"></h1>
                    </div>
                </div>
            </div>
        </div>
    </section>
</template>