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
                    <h4 class="font-bold text-2xl mb-2 text-center capitalize">Forgot Your Password?</h4>
                    <p class="text-muted text-center">Change your password in three easy steps. This helps to keep your new password secure.</p>
                    <form class="mt-6 space-y-4">
                        <div>
                            <label class="font-bold">Email Address</label>
                            <input type="text" class="form-input mt-2 rounded !bg-white border border-[#ced4da] text-base focus:border-custom" placeholder="Email Id">
                        </div>
                        <div>
                            <button type="submit" class="btn-custom w-full">Get New Password</button>
                        </div>
                    </form>
                </div>
                <div class="text-center mt-6">
                    <p><small class="text-white mr-2">Already have an account?</small> <NuxtLink to="login" class="text-white font-bold">Sign in</NuxtLink></p>
                </div>
            </div>
        </div>
    </section>
</template>