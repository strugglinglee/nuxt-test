<template>
    <header>
        <nav>
            <ul>
                <li>
                    <NuxtLink to="/about">关于</NuxtLink>
                </li>
                <li>
                    <NuxtLink to="/post/1">文章1</NuxtLink>
                </li>
                <li>
                    <NuxtLink to="/post/2">文章2</NuxtLink>
                </li>
            </ul>
        </nav>
    </header>
</template>

<script setup lang="ts">
useHead({
    title: '我的应用',
    meta: [
        { name: 'description', content: '我的神奇网站。' }
    ],
    bodyAttrs: {
        class: 'test'
    },
    script: [{ innerHTML: 'console.log(\'Hello world\')' }]
})
</script>

  