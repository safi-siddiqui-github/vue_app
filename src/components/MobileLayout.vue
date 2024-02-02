<script setup>

</script>
<template>
    <div class="flex justify-center">

        <div class="border-4 border-black rounded-3xl max-w-80 w-full h-[600px] overflow-hidden flex flex-col">

            <div class="flex px-5 py-2 items-center">

                <p class="font-semibold font-mono w-1/3">9:41</p>

                <div class="h-full w-1/3 rounded-full bg-black flex items-center justify-between px-2 gap-3">
                    <div class="rounded-full bg-white h-3 w-3 flex justify-center items-center">
                        <div class="p-0.5 bg-black rounded-full"></div>
                    </div>
                    <div class="rounded-full bg-white h-3 w-10 flex justify-center items-center">
                        <div class="p-0.5 bg-black rounded-full"></div>
                    </div>
                </div>

                <div class="flex items-center justify-end gap-0.5 w-1/3">
                    <img src="@/assets/icons/signal-strong-svgrepo-com.svg" alt="signal" class="h-5 w-5 object-contain">
                    <img src="@/assets/icons/wifi-svgrepo-com.svg" alt="wifi" class="h-4 w-4 object-contain mr-0.5">
                    <img src="@/assets/icons/battery-full-svgrepo-com.svg" alt="battery" class="h-5 w-5 object-contain">
                </div>
            </div>

            <div class="h-full w-full">
                <perfect-scrollbar>
                    <slot />
                </perfect-scrollbar>
            </div>

            <div class="flex px-6 py-2 justify-center items-center">
                <div class="w-1/3 border-2 border-black rounded-full"></div>
            </div>
        </div>

    </div>
</template>

<style>
.ps {
    height: 100%;
}
</style>