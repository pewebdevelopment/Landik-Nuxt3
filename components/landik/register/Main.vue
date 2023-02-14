<template>
     <section class="items-center flex bg-[url('/assets/images/login_bg.jpg')] bg-cover bg-center relative py-20 min-h-screen">
        <div class="bg-[#0d0f14]/25 absolute inset-0 backdrop-blur-md"></div>
        <div class="container relative">
            <div class="grid grid-cols-1">
                <div class="max-w-[450px] mx-auto">
                    <a href="index_1.html">
                        <img src="../../../assets/images/logo-light.png" alt="logo" class="mx-auto h-10">
                    </a>
                </div>
            </div>
            <div class="grid grid-cols-1 mt-16">
                <div class="max-w-[450px] mx-auto py-10 px-8 rounded-xl bg-white w-full">
                    <h4 class="font-bold text-2xl mb-2 text-center capitalize">Signup Now!</h4>
                    <p class="text-muted text-center">Registration takes less than a minute but gives you full control over your orders.</p>
                    <form class="mt-6 space-y-4">
                        <div>
                            <label class="font-bold">First Name</label>
                            <input type="text" class="form-input mt-2 rounded !bg-white border border-[#ced4da] text-base focus:border-custom" placeholder="First Name">
                        </div>
                        <div>
                            <label class="font-bold">Email Address</label>
                            <input type="text" class="form-input mt-2 rounded !bg-white border border-[#ced4da] text-base focus:border-custom" placeholder="Email Id">
                        </div>
                        <div>
                            <label class="font-bold">Password</label>
                            <input type="password" class="form-input mt-2 rounded !bg-white border border-[#ced4da] text-base focus:border-custom" placeholder="Password">
                        </div>
                        <div>
                            <input type="checkbox" class="form-checkbox border-[#ced4da] rounded focus:ring-transperent focus:outline-none h-4 w-4 text-custom" id="sign">
                            <label for="sign" class="ml-1 relative top-[2px]">I agree to the <a href="#" class="text-custom">Terams & Conditions</a></label>
                        </div>
                        <div>
                            <button type="submit" class="btn-custom w-full">Sign In</button>
                        </div>
                    </form>
                </div>
                <div class="text-center mt-6">
                    <p><small class="text-white mr-2">Already have an account?</small> <RouterLink to="/landik/login" class="text-white font-bold">Sign in</RouterLink></p>
                </div>
            </div>
        </div>
    </section>
</template>