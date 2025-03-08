<script lang="ts">
import { useRouter } from 'vue-router'
const inputHistory = () => {
    console.log("InputHistory")
    navigateTo({
        state: {conrtactSearchCondition: {
            name: "東海太郎",
            id: 1111
        }
        },
        replace: false,
        force:true
    })
}
</script>
<template>
    <div>
        <h1>検索ページ</h1>
        <NuxtLink to = "/price">
            <h2>priceページへ</h2>
        </NuxtLink>
        <NuxtLink to = "/serch">
            <h2>検索ページへ</h2>
        </NuxtLink>
    </div>
    <input>
    <button @click="inputHistory">
    </button>
</template>