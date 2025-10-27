<script>
	import Button from "$lib/components/button.svelte";
	import { resolve } from "$app/paths";
</script>

<svelte:head>
    <title>Holstebro Limousiner</title>
</svelte:head>

<div class="relative w-full">
    <img src={resolve("/LimoBG.png")} alt="" class="h-full w-full object-cover rounded-lg my-1">
    <div class="absolute inset-0 flex items-center justify-center">
        <p class="text-6xl text-gray-50 font-bold">Holstebro Limousine Service</p>
    </div>
</div>

<div class="text-gray-50 text-2xl mt-4 text-center">
Holstebro Limousine Service har tilbudt luksuriøs limousinekørsel
siden 1998.<br>
Vi kører til festlige lejligheder, hvor vi er med til at gøre jeres
dag endnu mere festlig og uforglemmelig.<br>
Hver kørsel aftales individuelt så oplevelsen bliver lige efter
jeres ønske.<br>
</div>

<div class="text-4xl flex justify-center my-3">
    <Button
        link={resolve("/book")}
        string="Book"
    />
</div>