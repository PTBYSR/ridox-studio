<script>
    export let card
</script>
<div class="border-[1px] border-black py-10 px-6 md:w-[400px] w-[300px] mx-5 md:h-[600px] h-[550px] flex flex-col justify-between">
    <div class="text-center">
        <h4 class="libre text-4xl">{card.plan}</h4>
        <p class="text-xs mt-4">{card.description}</p>
    </div>
    <div > 
        <ul class="flex flex-col gap-7 text-lg">
            <li>{card.features[0]}</li>
            <li>{card.features[1]}</li>
            <li>{card.features[2]}</li>
        </ul>
    </div>
    <div class="flex flex-col justify-center items-center">
        <p class="text-5xl text-center mb-10">{card.price}</p>
        <button><a href="http://wa.me/2348089849241">Let us talk on Whatsapp</a></button>
    </div>
</div>