<template>
    <footer id="contactId" class=" flex flex-col items-center footer footer-horizontal footer-center bg-white text-base-content rounded pt-10  lg:p-10 text-lg">
        <nav>
            <div class="flex flex-row justify-center gap-5">
                <a href="https://discord.gg/4muQxBsM" target="_blank">
                    <Icon :icon="'streamline-logos:discord-logo-2-solid'" class="text-gray-900" width="40" height="40" viewBox="0 0 24 24"></Icon>
                </a> 
                <a target="_blank" href="https://github.com/JustFr4nck">
                    <Icon :icon="'streamline-logos:github-logo-2-solid'" class="text-gray-900" width="40" height="40" viewBox="0 0 24 24"></Icon>
                </a> 
                <a target="_blank" href="https://www.linkedin.com/in/francesco-perrotta-228b28374/">
                    <Icon :icon="'streamline-logos:linkedin-logo-block'" class="text-gray-900" width="40" height="40" viewBox="0 0 24 24"></Icon>
                </a>
                <a target="_blank" href="https://t.me/Just_Fr4nck">
                    <Icon :icon="'streamline-logos:telegram-logo-2-solid'" class="text-gray-900" width="40" height="40" viewBox="0 0 24 24"></Icon>
                </a>
            </div>
        </nav>
        <aside class="flex flex-row text-center pt-2 lg:pb-1 pb-10 text-gray-900">
            <p>Copyright © JustFranck&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;|&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; perrotta.francesco.job@gmail.com</p>
        </aside>
    </footer>
</template>

<script setup lang="ts">

    import {Icon} from '@iconify/vue';

</script>