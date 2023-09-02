<template>
    <section class="pt-20 md:pt-24">
        <AtomsContainer>
            <div class="grid md:grid-cols-2 gap-10 xl:gap-14 relative">
                <div class="md:py-2 lg:py-4 relative">
                    <div class="absolute left-0 top-0 h-full w-full flex justify-end">
                        <span class="flex opacity-20">
                            <span class="w-16 h-32 rounded-l-full flex bg-primary blur-2xl"></span>
                            <span class="w-16 h-32 rounded-r-full flex bg-[#f88fc2] blur-2xl mt-14"></span>
                        </span>
                    </div>
                    <div class="relative">
                        <AtomsTitle texte="Wat te verwachten van Iris enthoven's Podcast?" />
                        <p class="text-gray-600 dark:text-gray-300 pt-8">
                            Lorem ipsum dolor sit amet consectetur adipisicing elit. Alias labore quas natus?
                            Repudiandae tempora autem corporis voluptatem ipsam voluptatibus
                        </p>
                        <div class="space-y-4 pt-8">
                            <div class="p-4 rounded-xl border border-box-border transition hover:bg-gray-200 dark:hover:bg-box-bg">
                                <h3 class="text-gray-700 dark:text-gray-200 font-semibold text-xl">Entertainment en Humor</h3>
                                <p class="text-base text-gray-600 dark:text-gray-300">Verwacht entertainment, humor en lichte gesprekken in Iris Enthoven's podcast.</p>
                            </div>
                            <div class="p-4 rounded-xl border border-box-border transition hover:bg-gray-200 dark:hover:bg-box-bg">
                                <h3 class="text-gray-700 dark:text-gray-200 font-semibold text-xl">Gasten en Discussies</h3>
                                <p class="text-base text-gray-600 dark:text-gray-300">Luister naar boeiende gesprekken met gasten uit diverse velden, van persoonlijke ervaringen tot popcultuur en trends.</p>
                            </div>
                            <div class="p-4 rounded-xl border border-box-border transition hover:bg-gray-200 dark:hover:bg-box-bg">
                                <h3 class="text-gray-700 dark:text-gray-200 font-semibold text-xl">Interactie met Publiek</h3>
                                <p class="text-base text-gray-600 dark:text-gray-300">Iris Enthoven betrekt haar publiek door vragen te beantwoorden, reacties te bespreken en fans te betrekken bij de podcast.</p>
                            </div>
                        </div>


                        <div class="pt-10 flex">
                            <AtomsLinkBtn href="#newpodcast" variant="primary">
                                Podcast luisteren
                            </AtomsLinkBtn>
                        </div>
                    </div>
                </div>
                <div class="flex md:h-full relative">
    <div class="absolute z-0 top-1/2 -translate-y-1/2 w-5/6 right-0 h-[calc(80%+20px)] bg-gradient-to-tr opacity-25 from-primary to-pink-300 dark:from-[#570cac] dark:to-primary blur-2xl"></div>
    <div class="w-full h-[27rem] sm:h-[30rem] md:h-full flex justify-start md:justify-end relative pb-5">
        <img src="/images/podCast.webp" alt="Podcast image" width="250" class="w-2/5 aspect-square absolute bottom-0 right-0 md:left-0 object-cover rounded-t-[30%] rounded-b-[30%] border-4 border-box-border shadow-md shadow-box-shadow">
        <img src="/images/others.webp" alt="Illustration about" width="200" class="w-3/5 lg:w-2/3 h-auto object-cover rounded-t-[8rem] rounded-b-[8rem] md:rounded-t-[10rem] md:rounded-b-[10rem] lg:rounded-t-[12rem] lg:rounded-b-[12rem]">
    </div>
</div>
            </div>
        </AtomsContainer>
    </section>
</template>