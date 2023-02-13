<template>
      <section class="py-20 bg-[url('assets/images/contact.jpg')] relative bg-cover">
        <div class="absolute inset-0 w-full h-full bg-dark/50"></div>
        <div class="container">
            <div class="grid grid-cols-1">
                <div class="bg-white md:py-20 md:px-[60px] px-5 py-[60px] relative max-w-[600px] md:ml-0 mx-auto rounded">
                    <div class="text-center">
                        <h2 class="font-bold text-[32px] md:text-[40px] capitalize mb-2 relative z-10"><span class="bg-[#dff1f0] h-[70px] w-[70px] inline-block absolute rounded-full -z-10 -top-[15px]"></span>Still Need Help?</h2>
                        <p class="mx-auto text-lg max-w-[600px] mt-6">Due to its widespread use as filler text for layouts, non-readability is of great importance.</p>
                        <div class="pt-12">
                            <button class="btn-custom w-3/4" onclick="toggleModal('modal-id')">Get In Touch</button>
                        </div>
                        <div>
                            <div class="hidden overflow-x-hidden overflow-y-auto fixed inset-0 z-50 outline-none focus:outline-none justify-center items-center" id="modal-id">
                                <div class="relative w-full my-6 mx-auto max-w-[500px]">
                                    <div class="rounded relative flex flex-col w-full bg-white outline-none focus:outline-none">
                                        <div class="flex items-center justify-between p-4 border-b border-[#dee2e6]">
                                            <h3 class="text-xl font-bold">
                                                Contact Us
                                            </h3>
                                            <button class="ml-auto bg-transparent border-0 text-dark" onclick="toggleModal('modal-id')">
                                                <span class="bg-transparent stroke-dark block">
                                                    <svg xmlns="http://www.w3.org/2000/svg" fill="none" viewBox="0 0 24 24" stroke-width="1.5" stroke="currentColor" class="w-5 h-5 stroke-dark">
                                                        <path stroke-linecap="round" stroke-linejoin="round" d="M6 18L18 6M6 6l12 12" />
                                                      </svg>
                                                      
                                                </span>
                                            </button>
                                        </div>
                                        <div class="relative p-3 flex-auto">
                                            <form class="space-y-6">
                                                <div>
                                                    <input type="text" class="form-input bg-[#f8f9fa] border !border-[#edf0f3] focus:!border-custom" placeholder="Your name..." required=false>
                                                </div>
                                                <div>
                                                    <input type="email" class="form-input bg-[#f8f9fa] border !border-[#edf0f3] focus:!border-custom" placeholder="Your email..." required=false>
                                                </div>
                                                <div>
                                                    <input type="text" class="form-input bg-[#f8f9fa] border !border-[#edf0f3] focus:!border-custom" placeholder="Your Subject.." required=false>
                                                </div>
                                                <div>
                                                    <textarea rows="4" class="form-input bg-[#f8f9fa] border !border-[#edf0f3] focus:!border-custom h-auto"  placeholder="Your message..." required=false></textarea>        
                                                </div>
                                                <button class="btn-custom w-full" type="submit">Send Message</button>
                                            </form>
                                        </div>
                                    </div>
                                </div>
                            </div>
                            <div class="hidden fixed inset-0 z-40 bg-dark/60" id="modal-id-backdrop"></div>
                        </div>
                    </div>
                </div>
            </div>
        </div>
    </section>
</template>