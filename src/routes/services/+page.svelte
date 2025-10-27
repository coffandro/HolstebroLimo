<script>
	import { resolve } from "$app/paths";
</script>

<svelte:head>
    <title>Service</title>
</svelte:head>

<div class="mt-8 w-full flex flex-col text-center">
    <p class="text-6xl text-gray-50 font-bold">Service</p>
</div>


<div class="mt-8 w-full flex flex-col">
    <p class="text-4xl text-gray-50 font-bold">Ford Lincoln Crystal Coach TownCar</p>
</div>

<div class="flex space-x-4 my-4">
    <div>
        <img src={resolve("/lilleBrudePar.jpg")} class="rounded-lg mb-2"/>
        <img src={resolve("/tjener01.jpg")} class="rounded-lg"/>
    </div>
    <div class="w-full text-gray-50 flex flex-col space-y-2">
        <p>Vi tilbyder uniformerede chaufør og limousine til den festlige lejlighed, lige meget om den er:</p>
        
        <div class="my-4 text-bold">
            <p>Kopper- sølv eller guldbryllup</p>
            <p>Fødselsdag</p>
            <p>Konfirmation</p>
            <p>Gallafest</p>
            <p>Polterabend</p>
            <p>Et vigtigt møde</p>
        </div>

        <p>Limousinekørsel er velgnet til at sætte rammen om jeres begivenheder - når alting skal være helt i orden.</p>
    </div>
</div>
