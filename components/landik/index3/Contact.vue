<template>
     <section class="py-20">
        <div class="container">
            <div class="grid grid-cols-1">
                <div class="text-center">
                    <h2 class="font-bold text-[32px] md:text-[40px] capitalize mb-2 relative z-10"><span class="bg-[#dff1f0] h-[70px] w-[70px] inline-block absolute rounded-full -z-10 -top-[15px]"></span>Get In Tuch With Us With Any Questions</h2>
                    <p class="text-muted mx-auto text-lg max-w-[600px] mt-6">Due to its widespread use as filler text for layouts, non-readability is of great importance.</p>
                </div>
            </div>
            <div class="grid grid-cols-1 mt-16">
                <div class="max-w-[500px] w-full mx-auto">
                    <form class="space-y-6">
                        <div>
                            <input type="email" class="form-input rounded-md !h-[55px] bg-white border !border-[#ced4da] focus:!border-custom" placeholder="Your email..." required=false>
                        </div>
                        <div>
                            <textarea rows="5" class="form-input rounded-md bg-white border !border-[#ced4da] focus:!border-custom h-auto" placeholder="Your message..." required=false spellcheck="false"></textarea>        
                        </div>
                        <div>
                            <button type="button" class="btn-custom w-full">Send Message</button>
                        </div>
                    </form>
                </div>
            </div>
            <div class="bg-dark/[0.04] h-[1px] my-[70px] w-full inline-block"></div>
            <div class="grid grid-cols-1 md:grid-cols-3 gap-[30px]">
                <div class="text-center">
                    <div class="bg-custom/20 w-[50px] h-[50px] flex items-center mx-auto justify-center leading-[50px] rounded-lg">
                        <img src="../../../assets/images/icon/mail.svg" alt="mail" class="mx-auto inline-block h-[30px]">
                    </div>
                    <h4 class="mt-4 font-bold text-xl">Email</h4>
                    <p class="mt-2 text-muted">information@gmail.com</p>
                </div>
                <div class="text-center">
                    <div class="bg-custom/20 w-[50px] h-[50px] flex items-center mx-auto justify-center leading-[50px] rounded-lg">
                        <img src="../../../assets/images/icon/active-call.svg" alt="mail" class="mx-auto inline-block h-[30px]">
                    </div>
                    <h4 class="mt-4 font-bold text-xl">Telephone</h4>
                    <p class="mt-2 text-muted">+(485) 874 249 23</p>
                </div>
                <div class="text-center">
                    <div class="bg-custom/20 w-[50px] h-[50px] flex items-center mx-auto justify-center leading-[50px] rounded-lg">
                        <img src="../../../assets/images/icon/time-schedule.svg" alt="mail" class="mx-auto inline-block h-[30px]">
                    </div>
                    <h4 class="mt-4 font-bold text-xl">Business Hours</h4>
                    <p class="mt-2 text-muted">Monday To Friday</p>
                    <p class="mt-1 text-muted">9:00am To 6:00pm (GMT)</p>
                </div>
            </div>
        </div>
    </section>
</template>