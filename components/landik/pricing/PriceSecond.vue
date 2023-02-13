<template>
     <section class="py-20 bg-white relative">
        <div class="container">
            <div class="grid grid-cols-1">
                <div class="text-center">
                    <h2 class="font-bold text-[32px] md:text-[40px] capitalize mb-2 relative z-10"><span class="bg-[#dff1f0] h-[70px] w-[70px] inline-block absolute rounded-full -z-10 -top-[15px]"></span>Choose The Right Plan For Your Landik</h2>
                    <p class="text-muted mx-auto text-lg max-w-[600px] mt-6">Due to its widespread use as filler text for layouts, non-readability is of great importance.</p>
                </div>
            </div>
            <div class="grid grid-cols-1 md:grid-cols-2 gap-[30px] mt-16 items-center">
                <div id="tab-buttons" class="space-y-[22px] ">
                    <a href="javascript:void(0)" onclick="changeTab(event, 0)" class="sm:flex active-price-tab space-y-[14px] block py-5 px-4 bg-white text-dark border-2 rounded-lg border-[#e7e7e7]/50 justify-between items-center">
                       <div class="text-center sm:text-left">
                            <h5 class="font-bold text-xl">Starter</h5>
                            <p class="bg-custom/20 text-custom py-1.5 px-3 rounded-full mt-2 inline-block text-[13px] active-price-tab-budges">20% Save</p>
                        </div>
                        <h2 class="text-[42px] text-center sm:text-right font-bold">$29<sub class="font-normal text-xs relative -bottom-1">/Per Month</sub></h2>
                    </a>
                    <a href="javascript:void(0)" onclick="changeTab(event, 1)" class="sm:flex space-y-[14px] block py-5 px-4 bg-white text-dark border-2 rounded-lg border-[#e7e7e7]/50 justify-between items-center">
                        <div class="text-center sm:text-left">
                             <h5 class="font-bold text-xl">Enterprice</h5>
                             <p class="bg-custom/20 text-custom py-1.5 px-3 rounded-full mt-2 inline-block text-[13px] active-price-tab-budges">25% Save</p>
                         </div>
                         <h2 class="text-[42px] text-center sm:text-right font-bold">$59<sub class="font-normal text-xs relative -bottom-1">/Per Month</sub></h2>
                     </a>
                     <a href="javascript:void(0)" onclick="changeTab(event, 2)" class="sm:flex space-y-[14px] block py-5 px-4 bg-white text-dark border-2 rounded-lg border-[#e7e7e7]/50 justify-between items-center">
                        <div class="text-center sm:text-left">
                             <h5 class="font-bold text-xl">Starter</h5>
                             <p class="bg-custom/20 text-custom py-1.5 px-3 rounded-full mt-2 inline-block text-[13px] active-price-tab-budges">30% Save</p>
                         </div>
                         <h2 class="text-[42px] text-center sm:text-right font-bold">$89<sub class="font-normal text-xs relative -bottom-1">/Per Month</sub></h2>
                     </a>
                </div>
                <div id="tab-panels">
                    <div class="md:max-w-[400px] mx-auto border border-[#e7e7e7]/60 relative overflow-hidden py-[60px] px-[46px] rounded-lg">
                        <div class="bg-custom/[0.07] w-[200px] h-[400px] absolute -top-[2px] inline-block -right-[130px] rounded-[20px] -rotate-[34deg]"></div>
                        <div class="space-y-[26px]">
                            <p class="mt-0 font-bold"><i class="mdi mdi-check-circle text-custom mr-1"></i> 2GB Cloud Storage</p>
                            <p class="mt-0 font-bold"><i class="mdi mdi-check-circle text-custom mr-1"></i> 100GB CDN Bandwidth</p>
                            <p class="mt-0 font-bold"><i class="mdi mdi-check-circle text-custom mr-1"></i> 98.88% Uptime Guarantee</p>
                            <p class="mt-0 font-bold"><i class="mdi mdi-check-circle text-custom mr-1"></i> Email Power Tools</p>
                        </div>
                        <div class="mt-12 text-right">
                            <a href="#" class="btn-custom rounded-full">Get Started</a>
                        </div>
                    </div>
                    <div class="md:max-w-[400px] hidden mx-auto border border-[#e7e7e7]/60 relative overflow-hidden py-[60px] px-[46px] rounded-lg">
                        <div class="bg-custom/[0.07] w-[200px] h-[400px] absolute -top-[2px] inline-block -right-[130px] rounded-[20px] -rotate-[34deg]"></div>
                        <div class="space-y-[26px]">
                            <p class="mt-0 font-bold"><i class="mdi mdi-check-circle text-custom mr-1"></i> 20GB Cloud Storage</p>
                            <p class="mt-0 font-bold"><i class="mdi mdi-check-circle text-custom mr-1"></i> 1TB CDN Bandwidth</p>
                            <p class="mt-0 font-bold"><i class="mdi mdi-check-circle text-custom mr-1"></i> 99.95% Uptime Guarantee</p>
                            <p class="mt-0 font-bold"><i class="mdi mdi-check-circle text-custom mr-1"></i> Personal Account Manager</p>
                        </div>
                        <div class="mt-12 text-right">
                            <a href="#" class="btn-custom rounded-full">Get Started</a>
                        </div>
                    </div>
                    <div class="md:max-w-[400px] hidden mx-auto border border-[#e7e7e7]/60 relative overflow-hidden py-[60px] px-[46px] rounded-lg">
                        <div class="bg-custom/[0.07] w-[200px] h-[400px] absolute -top-[2px] inline-block -right-[130px] rounded-[20px] -rotate-[34deg]"></div>
                        <div class="space-y-[26px]">
                            <p class="mt-0 font-bold"><i class="mdi mdi-check-circle text-custom mr-1"></i> 100TB CDN Bandwidth</p>
                            <p class="mt-0 font-bold"><i class="mdi mdi-check-circle text-custom mr-1"></i> API/Formulas Support*</p>
                            <p class="mt-0 font-bold"><i class="mdi mdi-check-circle text-custom mr-1"></i> 99.99% Uptime Guarantee</p>
                            <p class="mt-0 font-bold"><i class="mdi mdi-check-circle text-custom mr-1"></i> Enterprise SLA</p>
                        </div>
                        <div class="mt-12 text-right">
                            <a href="#" class="btn-custom rounded-full">Get Started</a>
                        </div>
                    </div>
                </div>
            </div>
        </div>
    </section>
</template>