<script>
    export let url = '/'
    export let label = ''
    export let color = 'gray'
</script>

<a href={url} class="text-base font-bold text-{color}-500 light:text-{color}-300 hover:underline">{label}</a>
