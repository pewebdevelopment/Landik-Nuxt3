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
                    <h4 class="font-bold text-2xl mb-2 text-center capitalize">Sign in</h4>
                    <p class="text-muted text-center">Sign in to your account using email and password provided during registration.</p>
                    <form class="mt-6 space-y-4">
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
                            <label for="sign" class="ml-1 relative top-[2px]">Keep me signed in</label>
                        </div>
                        <div>
                            <button type="submit" class="btn-custom w-full">Sign In</button>
                        </div>
                    </form>
                    <div class="mt-4 text-center">
                        <RouterLink to="pwreset" class="font-bold">Forgot your password ?</RouterLink>
                    </div>
                </div>
                <div class="text-center mt-6">
                    <p><small class="text-white mr-2">Don't have an account ?</small> <RouterLink to="register" class="text-white font-bold">Create an account</RouterLink></p>
                </div>
            </div>
        </div>
    </section>
</template>