<template>
    <header class="py-5">
        <div class="centered flex items-center">
            <nuxt-link to="/" class="app-logo max-w-[140px]">
                <img src="/img/logo.png" alt="amediatv-logo.png" />
            </nuxt-link>
            <div class="ml-auto flex items-center">
                <a href="/login" class="flex font-medium items-center gap-3">
                    <SvgIcon name="ic:round-login"></SvgIcon>
                    <span>Войти</span>
                </a>
            </div>
        </div>
    </header>
</template>
