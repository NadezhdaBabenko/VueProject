<template>
    <div class="text-center">
        <v-menu disabled offset-y>
            <template v-slot:activator="{ on }">
                <v-btn
                        color="transparent"
                        dark
                        v-on="on"
                >
                    Dropdown
                </v-btn>
            </template>
            <v-list>
                <v-list-item
                        v-for="(item, index) in items"
                        :key="index"
                >
                    <v-list-item-title>{{ item.title }}</v-list-item-title>
                </v-list-item>
            </v-list>
        </v-menu>
    </div>
</template>

<style>

</style>