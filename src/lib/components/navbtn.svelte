<script>
    import { page } from '$app/stores';

    export let string, link, isRight = false;
</script>

<a href={link} class="p-2 rounded-lg text-gray-50 {isRight ? "justify-self-end" : ""} {$page.url.pathname == link ? "bg-pink-900" : ""}">
    {string}
</a>