<script>
	import { resolve } from "$app/paths";
</script>

<svelte:head>
    <title>Priser</title>
</svelte:head>

<div class="mt-5 w-full flex flex-col text-center">
    <p class="text-6xl text-gray-50 font-bold">Første time fra kr. 2400,-</p>
    <p class="text-xl text-gray-50">Hver efterfulgt påbegyndte halve time kr. 600,00</p>
</div>

<div class="flex space-x-4 my-4">
    <div class="flex justify-end">
        <img src={resolve("/Drinks.png")} class="rounded-lg"/>
    </div>

    <div class="mt-5 w-full text-gray-50 flex flex-col space-y-2 mb-8">
        <p class="text-4xl font-bold">Kolde drikkevarer</p>
        <hr>

        <div class="grid grid-cols-2 justify-between *:odd:font-bold">
            <p>Super lækker Asti</p> <p>Kr. 150,- pr. fl.</p>
            <p>Spumante Brut</p> <p>Kr. 200,- pr. fl.</p>
            <p>Moet & Chandon</p> <p>Kr 600,- pr. fl.</p>
            <p>Alm. Whisky, Vodka, Bacardi rom</p> <p>Kr. 400,- pr. stk.</p>
            <p>Jack Daniels, Captain Morgan</p> <p>Kr. 400,- pr. stk.</p>
            <p>Redbull 25 cl.</p> <p>Kr. 30,-</p>
            <p>1 1/2 l. Coca Cola eller Faxe Kondi</p> <p>Kr. 50,- pr stk</p>
        </div>

        <div class="mt-8 font-bold">
            <p>Har du andre ønsker til drikkevarer, så sig endelig til.</p>
            <p>NB. Bemærk: Det er ikke tilladt at medbringe egne drikkevarer i limousinerne.</p>
        </div>
    </div>
</div>