<script>
    export let label = ''
    export let type = 'submit'
</script>


<div class="mt-6">
    <button class="w-full px-6 py-3 text-sm font-medium tracking-wide text-black capitalize transition-colors duration-300 transform bg-white-800 rounded-lg hover:bg-blue-700 focus:outline-none focus:ring focus:ring-gray-300 focus:ring-opacity-50 hover:text-white"
    type={type}>
        {label}
    </button>
</div>