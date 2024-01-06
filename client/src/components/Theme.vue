<template>
    <div class="w-14 h-8 flex items-center bg-gray-400 rounded-full p-1">
        <div class="w-6 h-6 bg-white rounded-full shadow-md">
        </div>
    </div>
</template>

<script>
import {useDark, useToggle} from '@vueuse/core'
const isDark = useDark();
const toggleDark = useToggle(isDark);
export default {
    name: 'Theme'
}
</script>