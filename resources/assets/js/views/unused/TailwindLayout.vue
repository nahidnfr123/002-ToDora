<template>
     <div>
        <!-- partial:index.partial.html -->
        <!-- Full width column -->
        <div class="flex mb-4">
            <div class="w-full bg-gray-300 h-12">
                <p class="text-center">
                    Hello this is the main app Vue.
                </p>
            </div>
        </div>

        <!-- Two columns -->
        <div class="flex mb-4">
            <div class="w-1/2 bg-gray-500 h-12"></div>
            <div class="w-1/2 bg-gray-300 h-12"></div>
        </div>

        <!-- Three columns -->
        <div class="flex mb-4">
            <div class="w-1/3 bg-gray-500 h-12"></div>
            <div class="w-1/3 bg-gray-300 h-12"></div>
            <div class="w-1/3 bg-gray-500 h-12"></div>
        </div>

        <!-- Four columns -->
        <div class="flex mb-4">
            <div class="w-1/4 bg-gray-300 h-12"></div>
            <div class="w-1/4 bg-gray-500 h-12"></div>
            <div class="w-1/4 bg-gray-300 h-12"></div>
            <div class="w-1/4 bg-gray-500 h-12"></div>
        </div>

        <!-- Five columns -->
        <div class="flex mb-4">
            <div class="w-1/5 bg-gray-300 h-12"></div>
            <div class="w-1/5 bg-gray-500 h-12"></div>
            <div class="w-1/5 bg-gray-300 h-12"></div>
            <div class="w-1/5 bg-gray-500 h-12"></div>
            <div class="w-1/5 bg-gray-300 h-12"></div>
        </div>

        <!-- Six columns -->
        <div class="flex">
            <div class="w-1/6 bg-gray-500 h-12"></div>
            <div class="w-1/6 bg-gray-300 h-12"></div>
            <div class="w-1/6 bg-gray-500 h-12"></div>
            <div class="w-1/6 bg-gray-300 h-12"></div>
            <div class="w-1/6 bg-gray-500 h-12"></div>
            <div class="w-1/6 bg-gray-300 h-12"></div>
        </div>
        <!-- partial -->
    </div>
</template>

<script>
export default {
    name:"TailwindLayout"
}
</script>
