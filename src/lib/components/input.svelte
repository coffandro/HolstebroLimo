<script>
    export let string, placeholder = "", rows = 1;
</script>

<div>
    <p class="mb-1 font-semibold text-gray-100">{string}</p>
    {#if rows == 1} 
        <input
            class="w-full p-3 rounded-lg bg-gray-200 text-gray-800 bg-pink-800"
            placeholder={placeholder ? placeholder : string} />
    {:else}
        <textarea
            rows={rows} 
            class="w-full p-3 rounded-lg bg-gray-200 text-gray-800 bg-pink-800"
            placeholder={placeholder ? placeholder : string}>
        </textarea>
    {/if}
</div>