<script setup>
import JetApplicationLogo from '@/Jetstream/ApplicationLogo.vue';
</script>

<template>
    <div>
        <div class="p-6 sm:px-20 bg-white border-b border-gray-200">
            <div>
                <JetApplicationLogo class="block h-12 w-auto" />
            </div>

            <div class="mt-8 text-2xl">
                Welcome to your Jetstream application!
            </div>

            <div class="mt-6 text-gray-500">
                <p>Nama : {{$page.props.user.name}}</p>
                <p>Email : {{$page.props.user.email}}</p>
                <p>Level : Admin</p>
            </div>
        </div>

    </div>
</template>
