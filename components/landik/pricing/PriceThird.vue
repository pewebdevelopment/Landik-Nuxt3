<template>
    <section class="py-20">
        <div class="container">
            <div class="grid grid-cols-1">
                <div class="text-center">
                    <h2 class="font-bold text-[32px] md:text-[40px] capitalize mb-2 relative z-10"><span
                            class="bg-[#dff1f0] h-[70px] w-[70px] inline-block absolute rounded-full -z-10 -top-[15px]"></span>Simple
                        Plan For Everyone</h2>
                    <p class="text-muted mx-auto text-lg max-w-[600px] mt-6">Due to its widespread use as filler text
                        for layouts, non-readability is of great importance.</p>
                </div>
            </div>
            <div class="grid grid-cols-1 mt-16">
                <div id="tab-buttons-two" class="flex items-center gap-3 justify-center">
                    <a href="javascript:void(0)" onclick="changePrice(event, 0)"
                        class="active-price-tab font-semibold rounded-[5px] block py-2 px-4 bg-white text-dark border-2 border-[#e7e7e7]/50">
                        Monthly
                    </a>
                    <a href="javascript:void(0)" onclick="changePrice(event, 1)"
                        class="font-semibold rounded-[5px] block py-2 px-4 bg-white text-dark border-2 border-[#e7e7e7]/50">
                        Yearly
                    </a>
                </div>
            </div>
            <div id="tab-panels-two">
                <div>
                    <div class="grid grid-cols-1 md:grid-cols-2 lg:grid-cols-3 gap-[30px] mt-12">
                        <div
                            class="border-2 text-center border-[#f1f1f1] relative overflow-hidden py-12 px-6 rounded-lg">
                            <h4 class="font-bold text-2xl">Landik Starter</h4>
                            <div class="py-6 space-x-2.5">
                                <i
                                    class="mdi mdi-star text-custom h-[30px] w-[30px] leading-[30px] rounded-md inline-block bg-custom/20"></i>
                            </div>
                            <p class="text-muted max-w-[300px] mx-auto">Nulla metus metus vel tincidunt sed euismod nibh
                                volutpat.</p>
                            <div class="h-px w-full bg-[#e7e7e7] my-12"></div>
                            <h3 class="font-bold mb-1 text-[40px]">$19.99</h3>
                            <p class="text-muted">Per Year</p>
                            <div class="mt-12">
                                <a href="#" class="btn-custom">Choose Plan</a>
                            </div>
                        </div>
                        <div
                            class="border-2 text-center border-[#f1f1f1] relative overflow-hidden py-12 px-6 rounded-lg">
                            <h4 class="font-bold text-2xl">Landik Enterprice</h4>
                            <div class="py-6 space-x-2.5">
                                <i
                                    class="mdi mdi-star text-custom h-[30px] w-[30px] leading-[30px] rounded-md inline-block bg-custom/20"></i>
                                <i
                                    class="mdi mdi-star text-custom h-[30px] w-[30px] leading-[30px] rounded-md inline-block bg-custom/20"></i>
                            </div>
                            <p class="text-muted max-w-[300px] mx-auto">Nulla metus metus vel tincidunt sed euismod nibh
                                volutpat.</p>
                            <div class="h-px w-full bg-[#e7e7e7] my-12"></div>
                            <h3 class="font-bold mb-1 text-[40px]">$29.99</h3>
                            <p class="text-muted">Per Year</p>
                            <div class="mt-12">
                                <a href="#" class="btn-custom">Choose Plan</a>
                            </div>
                        </div>
                        <div
                            class="border-2 text-center border-[#f1f1f1] relative overflow-hidden py-12 px-6 rounded-lg">
                            <h4 class="font-bold text-2xl">Landik Unlimited</h4>
                            <div class="py-6 space-x-2.5">
                                <i
                                    class="mdi mdi-star text-custom h-[30px] w-[30px] leading-[30px] rounded-md inline-block bg-custom/20"></i>
                                <i
                                    class="mdi mdi-star text-custom h-[30px] w-[30px] leading-[30px] rounded-md inline-block bg-custom/20"></i>
                                <i
                                    class="mdi mdi-star text-custom h-[30px] w-[30px] leading-[30px] rounded-md inline-block bg-custom/20"></i>
                            </div>
                            <p class="text-muted max-w-[300px] mx-auto">Nulla metus metus vel tincidunt sed euismod nibh
                                volutpat.</p>
                            <div class="h-px w-full bg-[#e7e7e7] my-12"></div>
                            <h3 class="font-bold mb-1 text-[40px]">$49.99</h3>
                            <p class="text-muted">Per Year</p>
                            <div class="mt-12">
                                <a href="#" class="btn-custom">Choose Plan</a>
                            </div>
                        </div>
                    </div>
                </div>
                <div class="hidden">
                    <div class="grid grid-cols-1 md:grid-cols-2 lg:grid-cols-3 gap-[30px] mt-12">
                        <div
                            class="border-2 text-center border-[#f1f1f1] relative overflow-hidden py-12 px-6 rounded-lg">
                            <h4 class="font-bold text-2xl">Landik Starter</h4>
                            <div class="py-6 space-x-2.5">
                                <i
                                    class="mdi mdi-star text-custom h-[30px] w-[30px] leading-[30px] rounded-md inline-block bg-custom/20"></i>
                            </div>
                            <p class="text-muted max-w-[300px] mx-auto">Nulla metus metus vel tincidunt sed euismod nibh
                                volutpat.</p>
                            <div class="h-px w-full bg-[#e7e7e7] my-12"></div>
                            <h3 class="font-bold mb-1 text-[40px]">$199.99</h3>
                            <p class="text-muted">Per Year</p>
                            <div class="mt-12">
                                <a href="#" class="btn-custom">Choose Plan</a>
                            </div>
                        </div>
                        <div
                            class="border-2 text-center border-[#f1f1f1] relative overflow-hidden py-12 px-6 rounded-lg">
                            <h4 class="font-bold text-2xl">Landik Enterprice</h4>
                            <div class="py-6 space-x-2.5">
                                <i
                                    class="mdi mdi-star text-custom h-[30px] w-[30px] leading-[30px] rounded-md inline-block bg-custom/20"></i>
                                <i
                                    class="mdi mdi-star text-custom h-[30px] w-[30px] leading-[30px] rounded-md inline-block bg-custom/20"></i>
                            </div>
                            <p class="text-muted max-w-[300px] mx-auto">Nulla metus metus vel tincidunt sed euismod nibh
                                volutpat.</p>
                            <div class="h-px w-full bg-[#e7e7e7] my-12"></div>
                            <h3 class="font-bold mb-1 text-[40px]">$299.99</h3>
                            <p class="text-muted">Per Year</p>
                            <div class="mt-12">
                                <a href="#" class="btn-custom">Choose Plan</a>
                            </div>
                        </div>
                        <div
                            class="border-2 text-center border-[#f1f1f1] relative overflow-hidden py-12 px-6 rounded-lg">
                            <h4 class="font-bold text-2xl">Landik Unlimited</h4>
                            <div class="py-6 space-x-2.5">
                                <i
                                    class="mdi mdi-star text-custom h-[30px] w-[30px] leading-[30px] rounded-md inline-block bg-custom/20"></i>
                                <i
                                    class="mdi mdi-star text-custom h-[30px] w-[30px] leading-[30px] rounded-md inline-block bg-custom/20"></i>
                                <i
                                    class="mdi mdi-star text-custom h-[30px] w-[30px] leading-[30px] rounded-md inline-block bg-custom/20"></i>
                            </div>
                            <p class="text-muted max-w-[300px] mx-auto">Nulla metus metus vel tincidunt sed euismod nibh
                                volutpat.</p>
                            <div class="h-px w-full bg-[#e7e7e7] my-12"></div>
                            <h3 class="font-bold mb-1 text-[40px]">$499.99</h3>
                            <p class="text-muted">Per Year</p>
                            <div class="mt-12">
                                <a href="#" class="btn-custom">Choose Plan</a>
                            </div>
                        </div>
                    </div>
                </div>
            </div>
        </div>
    </section>
</template>