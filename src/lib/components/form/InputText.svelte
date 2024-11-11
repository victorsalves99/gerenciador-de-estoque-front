<script>
    export let label = ""
    export let value
</script>



<div class="mt-4">
    <label class="block mb-2 text-sm font-medium text-gray-600 light:text-gray-200" for="LoggingEmailAddress">{label}</label>
    <input id="LoggingEmailAddress" class="block w-full px-4 py-2 text-gray-700 bg-white border rounded-lg light:bg-gray-800 light:text-gray-300 light:border-gray-600 focus:border-blue-400 focus:ring-opacity-40 light:focus:border-blue-300 focus:outline-none focus:ring focus:ring-blue-300" type="text" bind:value={value}/>
</div>