<script>
    import { page } from '$app/stores';
    import Device from "svelte-device-info";

    let isPhone = Device.isPhone;
</script>

<div class="w-full p-2 bg-pink-950 text-gray-50 grid content-center border-b-1 border-pink-900 {isPhone ? "rounded-bl-lg rounded-br-lg" : ""}">
    <a href="/">
        <b class="h-full text-4xl px-1 {$page.url.pathname == "/" ? "bg-pink-900 rounded-lg" : ""}">Holstebro Limousiner</b>
    </a>
</div>
