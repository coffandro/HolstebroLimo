<script>
	import Button from "$lib/components/button.svelte";
	import Datepicker from "$lib/components/datepicker.svelte";
	import Input from "$lib/components/input.svelte";
	import Timepicker from "$lib/components/timepicker.svelte";

</script>
<svelte:head>
    <title>Book</title>
</svelte:head>

<div class="mt-8 w-full flex flex-col text-center">
    <p class="text-6xl text-gray-50 font-bold">Book</p>
</div>

<div class="flex flex-col mx-2 space-y-2">
    <Input
        string="Navn"/>

    <div class="grid grid-cols-2 grid-rows-1 gap-2">
        <Input
            string="Email"/>
        <Input
            string="Mobil"/>
    </div>
    
    <p class="text-xl font-semibold text-gray-800 mt-4">
        Addresser inkl postnummer og by
    </p>
    <div class="grid grid-cols-2 grid-rows-1 gap-2">
        <Input
            string="Start Adresse"/>
        <Input
            string="Slut Adresse"/>
    </div>

    <p class="text-xl font-semibold text-gray-800 mt-4">
        Kørsels dato og tid
    </p>
    <div class="grid grid-cols-2 grid-rows-1 gap-2">
        <Datepicker
            string=""
            placeholder="Vælg dato"
        />
        <Timepicker
            string=""
            placeholder="00:00"
        />
    </div>
    <Input
        string="Evt. besked eller spørgsmål"
        rows={8}
        />
</div>

<div class="text-4xl flex justify-center mt-4 mb-8">
    <Button
        link="https://www.youtube.com/watch?v=dQw4w9WgXcQ"
        string="Send!"
    />
</div>