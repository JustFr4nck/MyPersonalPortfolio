<template>
    <footer id="contactId" class="footer footer-horizontal footer-center bg-[rgb(17,17,17)] text-base-content rounded p-10 text-lg">
        <nav>
            <div class="grid grid-flow-col gap-14">
                <a href="https://discord.gg/4muQxBsM" target="_blank">
                    <Icon :icon="'streamline-logos:discord-logo-2-solid'" class="fill-current" width="40" height="40" viewBox="0 0 24 24"></Icon>
                </a> 
                <a target="_blank" href="https://github.com/JustFr4nck">
                    <Icon :icon="'streamline-logos:github-logo-2-solid'" class="fill-current" width="40" height="40" viewBox="0 0 24 24"></Icon>
                </a> 
                <a target="_blank" href="https://www.linkedin.com/in/francesco-perrotta-228b28374/">
                    <Icon :icon="'streamline-logos:linkedin-logo-block'" class="fill-current" width="40" height="40" viewBox="0 0 24 24"></Icon>
                </a>
                <a target="_blank" href="https://t.me/Just_Fr4nck">
                    <Icon :icon="'streamline-logos:telegram-logo-2-solid'" class="fill-current" width="40" height="40" viewBox="0 0 24 24"></Icon>
                </a>
            </div>
        </nav>
        <aside>
            <p>Copyright © JustFranck&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;|&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; perrotta.francesco.job@gmail.com</p>
        </aside>
    </footer>
</template>

<script setup lang="ts">

    import {Icon} from '@iconify/vue';

</script>