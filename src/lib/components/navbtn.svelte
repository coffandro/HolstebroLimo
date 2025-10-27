<script>
    import { page } from '$app/stores';
    import { resolve } from "$app/paths";

    export let string, link, isRight = false;
</script>

<a href={resolve(link)} class="p-2 rounded-lg text-gray-50 {isRight ? "justify-self-end" : ""} {$page.url.pathname == link ? "bg-pink-900" : ""}">
    {string}
</a>