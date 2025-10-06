<script>
	import Button from "$lib/components/button.svelte";

</script>
<svelte:head>
    <title>Priser</title>
</svelte:head>

<div class="mt-5 w-full flex flex-col text-center">
    <p class="text-6xl text-gray-50 font-bold">Første time fra kr. 2400,-</p>
    <p class="text-xl text-gray-50">Hver efterfulgt påbegyndte halve time kr. 600,00</p>
</div>

<div class="text-4xl flex justify-center mt-8">
    <Button
        link="/book"
        string="Book"
    />
</div>

<div class="grid grid-cols-2 grid-rows-1 gap-2 my-4">
    <div class="flex justify-end">
        <img src="Drinks.png" class="rounded-lg"/>
    </div>

    <div class="mt-5 w-full text-gray-50 flex flex-col space-y-2 mb-8">
        <p class="text-4xl font-bold">Kolde drikkevarer</p>
        <p><b>Super lækker Asti</b> : Kr. 150,-</p>
        <p><b>Spumante Brut</b> : Kr. 200,-</p>
        <p><b>Moet & Chandon</b> : Kr 600,-</p>
        <p><b>Alm. Whisky, Vodka, Bacardi rom</b> : Kr. 400,- pr. stk.</p>
        <p><b>Inkl. 1 1/2 l. sodavand</b></p>
        <p><b>Jack Daniels, Captain Morgan</b> : Kr. 400,- pr. stk.</p>
        <p><b>Inkl. 1 1/2 l. sodavand</b></p>
        <p><b>Redbull 25 cl.</b> : Kr. 30,-</p>
        <p><b>1 1/2 l. Coca Cola eller Faxe Kondi</b> : Kr. 50,- pr stk</p>
        <p><b>Har du andre ønsker til drikkevarer, så sig endelig til.</b></p>
        <p><b>NB. Bemærk: Det er ikke tilladt at medbringe egne drikkevarer i limousinerne.</b></p>
    </div>
</div>