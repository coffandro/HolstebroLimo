<script>
    import Device from "svelte-device-info";
	import Navbtn from "./navbtn.svelte";
    import { PUBLIC_IS_PHONE } from "$env/static/public";

    let isPhone = PUBLIC_IS_PHONE == "true" ? true : Device.isPhone;
</script>


<div class="flex w-full p-3 bg-pink-950 {isPhone ? "justify-around fixed bottom-0 rounded-tl-lg rounded-tr-lg" : "rounded-bl-lg rounded-br-lg"}">
    <Navbtn link="/prices" string="Priser" />
    <Navbtn link="/limos" string="Limousiner" />
    {#if isPhone}
        <Navbtn link="/" string="Home" />    
    {/if}
    <Navbtn link="/services" string="Service" />
    <Navbtn link="/book" string="Book" isRight={!isPhone}/>
</div>