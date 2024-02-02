<script setup>
import MobileLayout from '@/components/MobileLayout.vue'
</script>
<template>
    <MobileLayout>
        <div class="flex flex-col h-full relative">
            <img src="@/assets/images/breno-assis-r3WAWU5Fi5Q-unsplash.jpg" alt="houses"
                class=" h-full object-cover w-full absolute top-0 left-0">

            <div class="flex flex-col h-full justify-between bg-black/60 z-10">

                <div class="flex gap-0.5 items-end justify-center pt-16">
                    <img src="@/assets/icons/house-floor-white-svgrepo-com.svg" alt="house" class="w-8">

                    <h3 class="text-2xl font-medium text-white tracking-tight">
                        Homes
                    </h3>
                </div>

                <div class="flex flex-col bg-white py-5 gap-5 px-5">

                    <div class="flex flex-col gap-1 text-center">
                        <p class="text-2xl font-medium tracking-tight">
                            Sign up for Homes
                        </p>

                        <p class="text-xs tracking-tight text-slate-500">
                            Discover perfect proeprty with easy-to-use app
                        </p>
                    </div>

                    <div class="flex flex-col gap-2">

                        <button class="flex items-center justify-center gap-2 border rounded-full py-2 hover:border-black">
                            <img src="@/assets/icons/google-color-svgrepo-com.svg" alt="google" class="w-5">
                            <p class="text-sm tracking-tight">Sign in with Google</p>
                        </button>

                        <button class="flex items-center justify-center gap-2 border rounded-full py-2 hover:border-black">
                            <img src="@/assets/icons/apple-173-svgrepo-com.svg" alt="apple" class="w-5">
                            <p class="text-sm tracking-tight">Sign in with Apple</p>
                        </button>
                    </div>

                    <div class="flex items-center gap-2.5 w-full">
                        <hr class="w-1/2">
                        <span>Or</span>
                        <hr class="w-1/2">
                    </div>

                    <div class="flex flex-col gap-4">
                        <button class="text-center text-white bg-black hover:bg-black/90 rounded-full py-2">
                            <p class="text-sm tracking-tight">Create new account</p>
                        </button>

                        <p class="text-sm font-medium text-center">Already have an account? <span class="text-blue-700">Login</span></p>
                    </div>

                </div>

            </div>

        </div>
    </MobileLayout>
</template>