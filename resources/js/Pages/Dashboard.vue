<script setup>
import BreezeAuthenticatedLayout from "@/Layouts/Authenticated.vue";
import BreezeButton from "@/Components/Button.vue";
import { Head } from "@inertiajs/inertia-vue3";
</script>

<template>
    <Head title="Dashboard" />

    <BreezeAuthenticatedLayout>
        <div class="py-24">
            <div class="max-w-7xl mx-auto sm:px-6 lg:px-8">
                <div class="columns-2 gap-20 auto-cols-auto">
                    <div>
                        <h1
                            class="font-medium leading-tight text-5xl mt-0 mb-2 text-slate-900 font-bold inline-block"
                        >
                            Booking lebih mudah dengan
                            <img
                                class="inline"
                                src="../../../public/img/bella-fix.png"
                                alt=""
                                width="120"
                            />
                        </h1>
                        <p class="pt-1">
                            Lorem, ipsum dolor sit amet consectetur adipisicing
                            elit. Voluptatem non dolorum ipsam fugiat adipisci
                            doloribus, illum distinctio, officiis temporibus
                            facilis tempore saepe repellendus eaque quaerat,
                            ipsa repudiandae placeat commodi dolore!
                        </p>
                        <BreezeButton>Show Room</BreezeButton>
                        <div class="columns-3 gap-5 auto-cols-auto mt-8">
                            <img
                                class=""
                                src="../../../public/img/bella-fix.png"
                                alt=""
                                width="50"
                            />
                            <p class="pt-1">18 Total Rooms</p>
                            <img
                                class=""
                                src="../../../public/img/bella-fix.png"
                                alt=""
                                width="50"
                            />
                            <img
                                class=""
                                src="../../../public/img/bella-fix.png"
                                alt=""
                                width="50"
                            />
                        </div>
                    </div>
                    <div>
                        <img
                            class="ml-24 rounded-tl-[160px] rounded-md"
                            src="../../../public/img/jumbotron.jpg"
                            alt=""
                            width="500"
                        />
                    </div>
                </div>
            </div>
        </div>
    </BreezeAuthenticatedLayout>
</template>
