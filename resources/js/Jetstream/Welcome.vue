<template>
    <div>
        <div class="p-6 sm:px-20 bg-white border-b border-gray-200">
            <div class="mt-8 text-2xl">
                Helllo an welcome (username) your last login was at (time date)
            </div>

            <div class="mt-8 text-2xl">Download file</div>

            <div class="mt-6 text-gray-500"></div>
        </div>
    </div>
</template>

<script>
import { defineComponent } from "vue";
import JetApplicationLogo from "@/Jetstream/ApplicationLogo.vue";

export default defineComponent({
    components: {
        JetApplicationLogo,
    },
});
</script>
