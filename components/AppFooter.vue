<template>
    <footer class="pt-20 bg-gray-100 dark:bg-body border-t border-gray-200 dark:border-gray-100/20">
        <AtomsContainer class-name="pb-10">
            <div class="grid grid-cols-2 md:grid-cols-4 lg:grid-cols-6 gap-8 gap-y-10">
                <div class="col-span-2 md:col-span-4 lg:col-span-2">
                    <NuxtLink to="/" class=" flex items-center gap-2">
                        <div class="inline-flex relative bg-inherit">
                    <NuxtLink to="/" class="flex items-center gap-2">
                        <img src="/logo.png" alt="App Logo" class="w-8 h-8 rounded-full object-cover">
                    </NuxtLink>
                </div>
                        <span class="text-xl font-bold text-gray-700 dark:text-white">Iris enthoven</span>
                    </NuxtLink>

                    <p class="text-gray-600 dark:text-gray-300 pt-6">
                        Ik ben niet verbonden aan Iris Enthoven, en deze website behoort niet aan haar toe.
                    </p>
                </div>

                <BlocksFooterNavBlock title="Socials" :links="quickLinks" />
                <BlocksFooterNavBlock title="Socials" :links="quickLinks2" />
                <BlocksFooterNavBlock title="Podcasts" :links="ressourcesLinks" />
                <BlocksFooterNavBlock title="Podcasts" :links="supportLinks" />
            </div>
        </AtomsContainer>
        <div class="py-2 bg-gray-200 dark:bg-[rgb(10,16,29)]">
            <AtomsContainer>
                <div class="flex justify-between items-center gap-5 text-gray-600 dark:text-gray-300">
                    <div class="">
                        Designed by <NuxtLink target="_blank"
                            to="https://pyramidion.dev" class="font-bold text-primary">Pyramidion</NuxtLink>
                    </div>
                </div>
            </AtomsContainer>
        </div>
    </footer>
</template>

<script lang="ts" setup>
const quickLinks = [
    {
        href: "https://facebook.com/irisenthoven",
        text: "Facebook"
    },
    {
        href: "https://instagram.com/irisenthoven",
        text: "Instagram"
    },
    {
        href: "https://twitter.com/Irisenthoven",
        text: "Twitter"
    }
]
const quickLinks2 = [
    {
        href: "https://youtube.com/irisenthoven",
        text: "YouTube"
    },
    {
        href: "#",
        text: "Over Iris"
    },
    {
        href: "https://podcasters.spotify.com/pod/show/iris-enthoven/subscribe",
        text: "Subscribe"
    }
]
const ressourcesLinks = [
    {
        href: "https://podcasts.apple.com/us/podcast/held-in-eigen-verhaal/id1533129732?uo=4",
        text: "Apple"
    },
    {
        href: "https://podcasts.google.com/feed/aHR0cHM6Ly9hbmNob3IuZm0vcy8zODI1NmMxOC9wb2RjYXN0L3Jzcw==",
        text: "Google"
    },
    {
        href: "https://overcast.fm/itunes1533129732/held-in-eigen-verhaal",
        text: "Overcast"
    }
]

const supportLinks = [
    {
        href: "https://pca.st/43hvo2d0",
        text: "Pocket Casts"
    },
    {
        href: "https://radiopublic.com/held-in-eigen-verhaal-6raMVq",
        text: "Radio Public"
    },
    {
        href: "https://open.spotify.com/show/1pfR1EbTZ8gwMLY6HbVJGk",
        text: "Spotify"
    }
]


</script>