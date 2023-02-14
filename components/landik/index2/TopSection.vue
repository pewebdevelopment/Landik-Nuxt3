<template>
     <section class="md:pt-[160px] md:pb-[170px] pt-[100px] pb-[120px] relative bg-cover bg-center bg-themedark">
        <div class="absolute inset-0 bg-cover bg-center bg-no-repeat w-full h-full bg-[url('../images/home_sec_layer-2.png')]"></div>
        <div class="container relative">
            <div class="grid grid-cols-1 lg:grid-cols-5 items-center gap-[30px]">
                <div class="lg:col-span-3">
                    <p class="py-2.5 px-5 bg-white/[0.03] italic inline-block rounded-lg text-custom mb-4 md:mb-0">Since 1911</p>
                    <h1 class="mt-4 md:text-[56px] text-[34px] leading-[1.2] text-white">Smart and effective solutions for businesses.</h1>
                    <p class="mt-6 text-lg text-white/40">Make a website you’ll be proud of.</p>
                    <div class="mt-12">
                        <a href="#" class="btn-custom rounded-none">See How It Works</a>
                    </div>
                    <div class="bg-white/[8%] w-full h-px block my-10 md:my-[50px]"></div>
                    <div class="sm:space-y-0 space-y-4">
                        <div class="items-center sm:inline-block block">
                            <span class="text-muted capitalize">Trusted partners:</span>
                        </div>
                        <div class="inline-block">
                            <img src="../../../assets/images/clients/6.png" alt="" class="h-[26px] my-2 mx-3 opacity-70 inline-block">
                            <img src="../../../assets/images/clients/7.png" alt="" class="h-[26px] my-2 mx-3 opacity-70 inline-block">
                        </div>
                    </div>
                </div>
                <div class="lg:col-span-2">
                    <div class="bg-white py-10 px-5 md:py-[60px] md:px-[30px] rounded">
                        <h2 class="text-center font-bold text-[32px]">Get 30 days FREE Trial</h2>
                        <p class="text-muted text-center mt-4">Landik offers functional contact forms that are fully customizable. Try it yourself!</p>
                        <form action="" class="mt-12 space-y-4">
                            <div>
                                <input type="text" class="form-input !border-none h-[52px]" placeholder="Your Name" required=false />
                            </div>
                            <div>
                                <input type="email" class="form-input !border-none h-[52px]" placeholder="Email Id" required=false />
                            </div>
                            <div>
                                <input type="text" class="form-input !border-none h-[52px]" placeholder="Mobile Number" required=false />
                            </div>
                            <button class="btn-custom rounded-none !mt-8 w-full" type="submit">Start Trial</button>
                        </form>
                    </div>
                </div>
            </div>
        </div>
    </section>
</template>