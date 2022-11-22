<script setup>
import emojiUrl from "./assets/emoji.jpeg"
import nechapesUrl from "./assets/nechapes.png"
import mitackyUrl from "./assets/mitacky.mp4"
</script>

<template>
<section class="mt-10 min-h-screen flex flex-col justify-center text-center">

<h1 class="text-2xl py-1 mb-10 text-pink-500 bg-black">VAZENI DOLAK! ANTI KK ANTI MM</h1>

<h2 class="text-xl text-purple-900 mb-2">PODPOR DOLAK V PRAZE ZUSTAT! DOLAK! NAJDI UBYTKO PRO KYNIKA!!!</h2>
<iframe class="mx-auto mb-10 rounded-md" width="175" height="315"
    src="https://www.youtube.com/embed/U8a-I58cXvQ" title="YouTube video player" frameborder="0"
    allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture"
    allowfullscreen></iframe>

<p class="text-sm py-2 max-w-prose mx-auto">
    Srdcervoucí příběh oběti naší doby. Teprve 19 letý mladík Antonín Dolák byl v noci z 9.
    na 10. listopadu napaden tepláčkami míťačkami když se pokoušel v klidu relaxovat. Prosím, rozšiřme povědomí
    o tepláčkách míťačkách, aby nedošlo k dalším takovým útokům.
</p>
<div class="mx-auto">
    <video
        controls
        :src="mitackyUrl" type="video/mp4"
        class="md:m-5 w-full max-w-md md:rounded-md shadow-lg"
    >
    </video>
</div>
<p class="text-sm py-2 max-w-prose mx-auto">
    Prosím, už mu nedělej mítů1!!!+!! prosim!!! PRESTAN MU DELAT MEETU 😭😭😭
</p>

</section>
<section class="mt-10 p-5">

<div class="inline-flex gap-2">
    <p>Kontakt pan DOlak</p>
    <img :src="emojiUrl" alt="emoji" />
</div>
<a class="underline hover:no-underline text-blue-700" href="mailto:dolakantonin@gmail.com">dolakantonin@gmail.com</a>
<p class="mb-10 mx-5 text-red-500 bg-black">U{POZORNENI!!} DOLAK NECHATUJE.! POUZE SRAZY!</p>

<div class="mx-auto">
    <img class="w-full h-32 md:h-64" :src="nechapesUrl">
</div>

<p class="text-center font-bold text-purple-900">DOLAK SWAG!! NECHAPES BEJB!!</p>

</section>
</template>
