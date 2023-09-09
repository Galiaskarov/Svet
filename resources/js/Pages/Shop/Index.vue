<script setup>
import MainLayout from "@/Layouts/MainLayout.vue";
import {Head, Link} from "@inertiajs/vue3";
import Content from "@/Components/Content.vue";

</script>

<template>
    <MainLayout>
        <Head title="Shop"/>
        <Content>
            <h1 class="text-xl font-black text-amber-500">Shop page</h1>
            <ul class="mt-5">
                <li class="flex justify-between border-b border-x-cyan-600 pb-1.5 mb-4">
                    <span class="text-cyan-600">Продукт 1</span>
                    <div class="flex gap-3">
                        <Link class="text-emerald-500">
                            Купить
                        </Link>
                        <Link class="text-amber-500">
                            Подробнее
                        </Link>
                        <Link class="text-red-500">
                            Оставить отзыв
                        </Link>
                    </div>
                </li>
            </ul>
        </Content>
    </MainLayout>
</template>

<style scoped>

</style>
