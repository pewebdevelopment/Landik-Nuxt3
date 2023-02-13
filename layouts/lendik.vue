<template>
     <header>
        <nav class="navbar navbar-expand-lg navbar-light fixed w-full horizontal-nav">
            <div class="container">
                <div class="flex items-center justify-between">
                    <NuxtLink class="navbar-brand" href="lendik/index_1">
                        <img src="../assets/images/logo-dark.png" class="mr-2 w-[130px]" alt="logo">
                    </NuxtLink>
                    <button class="navbar-toggler hidden text-end mobile-menu-button">
                        <span class="navbar-toggler-icon">
                            <i class="ti-menu icon-align-right"></i>
                        </span>
                    </button>
                    <div class="navbar-collapse flex-1 mobile-menu hidden min-[991px]:block" id="navbarNav">
                        <ul class="navbar-nav justify-end horizontal-menu">
                            <li class="scroll dropdown active group/menu">
                                <NuxtLink href="lendik/javaScript:void();" class="dropdown-toggle"><span>Landing</span></NuxtLink>
                                <ul class="dropdown-menu hidden group-hover/menu:block">
                                    <li><NuxtLink href="lendik/index_1">Landing Page 1</NuxtLink></li>
                                    <li><NuxtLink href="lendik/index_2">Landing Page 2</NuxtLink></li>
                                    <li><NuxtLink href="lendik/index_3">Landing Page 3</NuxtLink></li>
                                    <li><NuxtLink href="lendik/index_4">Landing Page 4</NuxtLink></li>
                                </ul>
                            </li>
                            <li class="scroll dropdown group/menu">
                                <NuxtLink href="lendik/javaScript:void();" class="dropdown-toggle"><span>Pages</span></NuxtLink>
                                <ul class="dropdown-menu hidden group-hover/menu:block">
                                    <li><NuxtLink href="lendik/about">About</NuxtLink></li>
                                    <li><NuxtLink href="lendik/service">Service</NuxtLink></li>
                                    <li class="dropdown group/submenu">
                                        <NuxtLink href="lendik/javaScript:void();" class="dropdown-toggle">Widget</NuxtLink>
                                        <ul class="dropdown-menu hidden group-hover/submenu:block">
                                            <li><NuxtLink href="lendik/pricing">Pricing</NuxtLink></li>
                                            <li><NuxtLink href="lendik/testimonial">Testimonial</NuxtLink></li>
                                            <li><NuxtLink href="lendik/faqs">FAQs</NuxtLink></li>
                                        </ul>
                                    </li>
                                    <li><NuxtLink href="lendik/contact">Contact</NuxtLink></li>
                                </ul>
                            </li> 
                            <li class="scroll dropdown group/menu">
                                <NuxtLink href="lendik/javaScript:void();" class="dropdown-toggle"><span>Account</span></NuxtLink>
                                <ul class="dropdown-menu hidden group-hover/menu:block">
                                    <li><NuxtLink href="lendik/login">Login</NuxtLink></li>
                                    <li><NuxtLink href="lendik/ragister">Ragister</NuxtLink></li>
                                    <li><NuxtLink href="lendik/pwreset">Password Reset</NuxtLink></li>
                                </ul>
                            </li>                           
                            <li class="scroll dropdown group/menu">
                                <NuxtLink href="lendik/javaScript:void();" class="dropdown-toggle"><span>Docs</span></NuxtLink>
                                <ul class="dropdown-menu hidden group-hover/menu:block">
                                    <li><NuxtLink href="lendik/documentation">Documentation</NuxtLink></li>
                                    <li><NuxtLink href="lendik/changelog">Changelog</NuxtLink></li>
                                </ul>
                            </li>
                            <button class="btn btn-sm btn-custom navbar-btn btn-rounded">Buy Now</button>
                        </ul>
                    </div>
                </div>
            </div>
        </nav>
    </header>
    <div>
        <slot />
    </div>
    <footer class="bg-themedark pt-[60px] pb-[30px]">
        <div class="container">
            <div class="items-center grid md:grid-cols-2 grid-cols-1 gap-[30px]">
                <div>
                    <img src="../assets/images/logo-light.png" alt="" class="h-[30px] mx-auto md:ml-0" />
                </div>
                <div>
                    <form class="relative mx-auto md:mr-0 max-w-[380px]">
                        <input type="text" class="py-[14px] px-[15px] w-full text-sm outline-none pr-[150px] pl-5 rounded-[6px] text-white bg-white/[0.04] border border-white/[0.001]" placeholder="Email" />
                        <button type="submit" class="absolute tracking-[1px] font-normal text-[15px] rounded-[5px] capitalize top-1 right-1 outline-none text-sm py-[10px] px-[30px] bg-custom text-white border border-custom">
                            Subcribe
                        </button>
                    </form>
                </div>
            </div>
            <div class="bg-white/[0.07] h-[1px] w-full my-10 mt-12"></div>
            <div class="grid grid-cols-1 md:grid-cols-2 gap-[30px] items-center">
                <div>
                    <ul class="flex md:flex-row flex-col gap-y-2.5 items-center text-center md:text-left">
                        <li class="text-white hover:text-custom after:hidden duration-300 md:after:inline-block md:after:text-white md:after:mx-5 md:after:top-1 md:after:relative md:after:content-['*']">
                            <NuxtLink href="lendik/#">Demo</NuxtLink>
                        </li>
                        <li class="text-white hover:text-custom after:hidden duration-300 md:after:inline-block md:after:text-white md:after:mx-5 md:after:top-1 md:after:relative md:after:content-['*']">
                            <NuxtLink href="lendik/#">Pages</NuxtLink>
                        </li>
                        <li class="text-white hover:text-custom duration-300"><NuxtLink href="lendik/#">Support</NuxtLink></li>
                    </ul>
                </div>
                <div>
                    <ul class="flex items-center space-x-3 md:justify-end justify-center">
                        <li>
                            <NuxtLink href="lendik/#" class="text-white w-[38px] h-[38px] leading-[38px] hover:text-custom duration-300 hover:-translate-y-1 rounded-full block bg-white/5 text-lg text-center"><i class="mdi mdi-facebook"></i></NuxtLink>
                        </li>
                        <li>
                            <NuxtLink href="lendik/#" class="text-white w-[38px] h-[38px] leading-[38px] hover:text-custom duration-300 hover:-translate-y-1 rounded-full block bg-white/5 text-lg text-center"><i class="mdi mdi-twitter"></i></NuxtLink>
                        </li>
                        <li>
                            <NuxtLink href="lendik/#" class="text-white w-[38px] h-[38px] leading-[38px] hover:text-custom duration-300 hover:-translate-y-1 rounded-full block bg-white/5 text-lg text-center"><i class="mdi mdi-reddit"></i></NuxtLink>
                        </li>
                    </ul>
                </div>
            </div>
            <div class="grid grid-cols-1 mt-4">
                <div class="col-lg-12">
                    <div class="text-center mt-4 bg-white/[0.03] py-3.5 px-3 rounded">
                        <p class="text-white">&copy; 2023 Landik. Design and coded by ThemesBoss.</p>
                    </div>
                </div>
            </div>
        </div>
    </footer>
</template>