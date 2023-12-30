<script setup>
    import Card from "@/components/CardComponent.vue";
</script>

<template>
    <header class="w-full flex justify-center mt-20">
        <section class="max-w-[500px] flex flex-col items-center justify-center">
            <img src="../assets/me.webp" alt="Moi" class="w-full max-w-[25%] rounded-full">
            <h1 class="mt-2 text-gray-200 text-3xl font-semibold">Mathieu Le Puil</h1>
            <h2 class="mt-2 text-gray-400 text-ml">Développeur Symfony | VueJS | Tailwind</h2>
        </section>
  </header>

    <main class="flex flex-col justify-center items-center mt-12">
        <section class="max-w-[300px] sm:max-w-[400px]">
            <Card link="https://github.com/mathieulepuil" logo="https://link.mathieulp.fr/assets/logo_github.webp" color="gray-700" title="Mon Github" class="cursor-pointer" />
            <Card link="https://linkedin.com/in/mathieulepuil" logo="https://link.mathieulp.fr/assets/logo_linkedin.webp" color="blue-500" title="Mon Linkedin" class="cursor-pointer" />
            <Card link="https://twitter.com/mathieulepuil" logo="https://link.mathieulp.fr/assets/x.webp" color="blue-300" title="Mon Twitter" class="cursor-pointer" />
            <Card link="https://mathieulp.fr/" logo="https://link.mathieulp.fr/assets/website.webp" color="pink-300" title="Mon site web" class="cursor-pointer" />
            <Card link="mailto:contact@mathieulp.fr" logo="https://link.mathieulp.fr/assets/email.webp" color="red-400" title="Me contacter" class="cursor-pointer" />
        </section>

    </main>
</template>
