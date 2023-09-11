<template>
<v-app>
    <!-- Sidebar -->
    <v-navigation-drawer app v-model="drawer" color="grey lighten-4" :width="customWidth" style="background-color:#0f1724 !important">
        <!-- Sidebar Content -->
        <div>
            <img class="img-fluid" :src="imagePath" alt="dfg" />

        </div>
        <v-list>

            <v-list-item link class="list-item">
                <v-list-item-icon>
                    <v-icon>mdi-home</v-icon>
                </v-list-item-icon>
                <v-list-item-content>
                    <v-list-item-title>Home</v-list-item-title>
                </v-list-item-content>
            </v-list-item>

            <v-list-item link :to="{ name: 'Programs' }" class="list-item">
                <v-list-item-icon>
                    <v-icon>mdi-account</v-icon>
                </v-list-item-icon>
                <v-list-item-content>
                    <v-list-item-title>Profile</v-list-item-title>
                </v-list-item-content>
            </v-list-item>

            <v-list-item link :to="{ name: 'Programs' }" class="list-item">
                <v-list-item-icon>
                    <v-icon>mdi-account</v-icon>
                </v-list-item-icon>
                <v-list-item-content>
                    <v-list-item-title>Profile</v-list-item-title>
                </v-list-item-content>
            </v-list-item>

            <v-list-item link :to="{ name: 'Programs' }" class="list-item">
                <v-list-item-icon>
                    <v-icon>mdi-account</v-icon>
                </v-list-item-icon>
                <v-list-item-content>
                    <v-list-item-title>Profile</v-list-item-title>
                </v-list-item-content>
            </v-list-item>

            <v-list-item link :to="{ name: 'Programs' }" class="list-item">
                <v-list-item-icon>
                    <v-icon>mdi-account</v-icon>
                </v-list-item-icon>
                <v-list-item-content>
                    <v-list-item-title>Profile</v-list-item-title>
                </v-list-item-content>
            </v-list-item>

            <v-list-item link :to="{ name: 'Programs' }" class="list-item">
                <v-list-item-icon>
                    <v-icon>mdi-account</v-icon>
                </v-list-item-icon>
                <v-list-item-content>
                    <v-list-item-title>Profile</v-list-item-title>
                </v-list-item-content>
            </v-list-item>

            <v-list-item link :to="{ name: 'Programs' }" class="list-item">
                <v-list-item-icon>
                    <v-icon>mdi-account</v-icon>
                </v-list-item-icon>
                <v-list-item-content>
                    <v-list-item-title>Profile</v-list-item-title>
                </v-list-item-content>
            </v-list-item>
            <v-list-item link :to="{ name: 'Programs' }" class="list-item">
                <v-list-item-icon>
                    <v-icon>mdi-account</v-icon>
                </v-list-item-icon>
                <v-list-item-content>
                    <v-list-item-title>Profile</v-list-item-title>
                </v-list-item-content>
            </v-list-item>

            <v-list-item link :to="{ name: 'Programs' }" class="list-item">
                <v-list-item-icon>
                    <v-icon>mdi-account</v-icon>
                </v-list-item-icon>
                <v-list-item-content>
                    <v-list-item-title>Profile</v-list-item-title>
                </v-list-item-content>
            </v-list-item>
            <v-list-item link :to="{ name: 'Programs' }" class="list-item">
                <v-list-item-icon>
                    <v-icon>mdi-cog</v-icon>
                </v-list-item-icon>
                <v-list-item-content>
                    <v-list-item-title>Settings</v-list-item-title>
                </v-list-item-content>
            </v-list-item>
        </v-list>
    </v-navigation-drawer>

    <!-- Main Content -->
    <v-app-bar app color="grey lighten-4" style="background-color:#090e18 !important">
        <!-- Toggle Button -->
        <v-btn icon @click="toggleDrawer">
            <v-icon>mdi-menu</v-icon>
        </v-btn>

        <!-- Navbar Title -->
        <v-toolbar-title>
            <v-card class="mx-auto borderr" color="grey-lighten-3" max-width="300" style="background-color: red;">

                <v-text-field :loading="loading" density="compact" variant="solo" label="Search Anythings" append-inner-icon="mdi-magnify" single-line hide-details @click:append-inner="onClick"></v-text-field>

            </v-card>
        </v-toolbar-title>

        <!-- Other Navbar Buttons -->
        <v-spacer></v-spacer>

        <v-btn icon>
            <v-icon>mdi-weather-night</v-icon> <!-- Use mdi-weather-night for the moon icon -->
        </v-btn>

        <v-btn icon>
            <v-icon>mdi-bell</v-icon>
        </v-btn>

        <v-btn icon>
            <v-icon>mdi-account</v-icon> <!-- Replace with your profile icon -->
        </v-btn>

    </v-app-bar>

    <!-- Main Content -->
    <v-main>
        <v-container fluid style="background-color:#010812">

            <v-row>
                <v-col md="3" sm="6" xs="6">
                    <v-card class="mx-auto cardcolor" max-width="368">

                        <v-card-text class="py-0">
                            <v-row align="center" no-gutters>
                                <v-col class="text-left" cols="6">
                                    <p style="font-size: 15px; font-weight:400">Attached</p>

                                    <p style="font-size: 20px; font-weight:400" class="pt-2">Staff</p>
                                </v-col>

                                <v-col cols="6" class="text-right">

                                    <p class="mt-5 mb-5" style="font-size:40px !important">6</p>
                                </v-col>
                            </v-row>
                        </v-card-text>
                    </v-card>
                </v-col>
                <v-col md="3" sm="6" xs="6">
                    <v-card class="mx-auto cardcolor" max-width="368">

                        <v-card-text class="py-0">
                            <v-row align="center" no-gutters>
                                <v-col class="text-left" cols="6">
                                    <p style="font-size: 15px; font-weight:400">Attached</p>

                                    <p style="font-size: 20px; font-weight:400" class="pt-2">Staff</p>
                                </v-col>

                                <v-col cols="6" class="text-right">

                                    <p class="mt-5 mb-5" style="font-size:40px !important">6</p>
                                </v-col>
                            </v-row>
                        </v-card-text>
                    </v-card>

                </v-col>
                <v-col md="3" sm="6" xs="6">
                    <v-card class="mx-auto cardcolor" max-width="368">

                        <v-card-text class="py-0">
                            <v-row align="center" no-gutters>
                                <v-col class="text-left" cols="6">
                                    <p style="font-size: 15px; font-weight:400">Attached</p>

                                    <p style="font-size: 20px; font-weight:400" class="pt-2">Staff</p>
                                </v-col>

                                <v-col cols="6" class="text-right">

                                    <p class="mt-5 mb-5" style="font-size:40px !important">6</p>
                                </v-col>
                            </v-row>
                        </v-card-text>
                    </v-card>
                </v-col>
                <v-col md="3" sm="6" xs="6">
                    <v-card class="mx-auto cardcolor" max-width="368">

                        <v-card-text class="py-0">
                            <v-row align="center" no-gutters>
                                <v-col class="text-left" cols="6">
                                    <p style="font-size: 15px; font-weight:400">Attached</p>

                                    <p style="font-size: 20px; font-weight:400" class="pt-2">Staff</p>
                                </v-col>

                                <v-col cols="6" class="text-right">

                                    <p class="mt-5 mb-5" style="font-size:40px !important">6</p>
                                </v-col>
                            </v-row>
                        </v-card-text>
                    </v-card>
                </v-col>
            </v-row>

        </v-container>
    </v-main>

    <!-- next section -->
    <v-main style="background-color:#010812" class=" pt-0">
        <v-container fluid class="mt-0 py-0">
            <v-row>
                <v-col cols="12" md="3">
                    <v-card :loading="loading" class="mx-auto" max-width="">
                        <template v-slot:loader="{ isActive }">
                            <v-progress-linear :active="isActive" color="deep-purple" height="4" indeterminate></v-progress-linear>
                        </template>

                        <v-card-item>
                            <v-card-title class="text-left">Overview</v-card-title>
                        </v-card-item>

                        <v-card-text>
                            <v-row class="mx-0">
                                <v-col cols="12" md="4">
                                    <p > Programs Posted</p>
                                    <h2>14</h2>
                                </v-col>
                                <v-col cols="12" md="4">
                                  <p>Programs Posted</p>
                                  <h2>4</h2>

                                </v-col>
                                <v-col cols="12" md="4">
                                  <p>Programs Posted</p>
                                  <h2>0</h2>

                                </v-col>
                            </v-row>
                            <div class="text-left my-12 text-subtitle-1">
                                $ • Italian, Cafe
                            </div>

                            <div>Small plates, salads & sandwiches - an intimate setting with 12 indoor seats plus patio seating.</div>
                        </v-card-text>

                        <v-divider class="mx-4 mb-1"></v-divider>

                        <v-card-title>Tonight's availability</v-card-title>

                        <div class="px-4">
                            <v-chip-group v-model="selection">
                                <v-chip>5:30PM</v-chip>

                                <v-chip>7:30PM</v-chip>

                                <v-chip>8:00PM</v-chip>

                                <v-chip>9:00PM</v-chip>
                            </v-chip-group>
                        </div>

                        <v-card-actions>
                            <v-btn color="deep-purple-lighten-2" variant="text" @click="reserve">
                                Reserve
                            </v-btn>
                        </v-card-actions>
                    </v-card>
                </v-col>

                <v-col cols="12" md="6">
                    <v-card :loading="loading" class="mx-auto" max-width="">
                        <template v-slot:loader="{ isActive }">
                            <v-progress-linear :active="isActive" color="deep-purple" height="4" indeterminate></v-progress-linear>
                        </template>

                        <v-img cover height="250" src="https://cdn.vuetifyjs.com/images/cards/cooking.png"></v-img>

                        <v-card-item>
                            <v-card-title>Cafe Badilico</v-card-title>

                            <v-card-subtitle>
                                <span class="me-1">Local Favorite</span>

                                <v-icon color="error" icon="mdi-fire-circle" size="small"></v-icon>
                            </v-card-subtitle>
                        </v-card-item>

                        <v-card-text>
                            <v-row align="center" class="mx-0">
                                <v-rating :model-value="4.5" color="amber" density="compact" half-increments readonly size="small"></v-rating>

                                <div class="text-grey ms-4">
                                    4.5 (413)
                                </div>
                            </v-row>

                            <div class="my-4 text-subtitle-1">
                                $ • Italian, Cafe
                            </div>

                            <div>Small plates, salads & sandwiches - an intimate setting with 12 indoor seats plus patio seating.</div>
                        </v-card-text>

                        <v-divider class="mx-4 mb-1"></v-divider>

                        <v-card-title>Tonight's availability</v-card-title>

                        <div class="px-4">
                            <v-chip-group v-model="selection">
                                <v-chip>5:30PM</v-chip>

                                <v-chip>7:30PM</v-chip>

                                <v-chip>8:00PM</v-chip>

                                <v-chip>9:00PM</v-chip>
                            </v-chip-group>
                        </div>

                        <v-card-actions>
                            <v-btn color="deep-purple-lighten-2" variant="text" @click="reserve">
                                Reserve
                            </v-btn>
                        </v-card-actions>
                    </v-card>
                </v-col>

                <v-col cols="12" md="3">
                    <v-card :loading="loading" class="mx-auto" max-width="">
                        <template v-slot:loader="{ isActive }">
                            <v-progress-linear :active="isActive" color="deep-purple" height="4" indeterminate></v-progress-linear>
                        </template>

                        <!-- <v-img cover height="250" src="https://cdn.vuetifyjs.com/images/cards/cooking.png"></v-img> -->

                        <v-card-item>
                            <v-card-title>Cafe Badilico</v-card-title>

                            <v-card-subtitle>
                                <span class="me-1">Local Favorite</span>

                                <v-icon color="error" icon="mdi-fire-circle" size="small"></v-icon>
                            </v-card-subtitle>
                        </v-card-item>

                        <v-card-text>
                            <v-row align="center" class="mx-0">
                                <v-rating :model-value="4.5" color="amber" density="compact" half-increments readonly size="small"></v-rating>

                                <div class="text-grey ms-4">
                                    4.5 (413)
                                </div>
                            </v-row>

                            <div class="my-4 text-subtitle-1">
                                $ • Italian, Cafe
                            </div>

                            <div>Small plates, salads & sandwiches - an intimate setting with 12 indoor seats plus patio seating.</div>
                        </v-card-text>

                        <v-divider class="mx-4 mb-1"></v-divider>

                        <v-card-title>Tonight's availability</v-card-title>

                        <div class="px-4">
                            <v-chip-group v-model="selection">
                                <v-chip>5:30PM</v-chip>

                                <v-chip>7:30PM</v-chip>

                                <v-chip>8:00PM</v-chip>

                                <v-chip>9:00PM</v-chip>
                            </v-chip-group>
                        </div>

                        <v-card-actions>
                            <v-btn color="deep-purple-lighten-2" variant="text" @click="reserve">
                                Reserve
                            </v-btn>
                        </v-card-actions>
                    </v-card>
                </v-col>
            </v-row>
        </v-container>
    </v-main>
</v-app>
</template>

<script>
import downloadImage from '@/assets/download1.png'; // Import the image

export default {
    name: "DashboardD",
    data() {
        return {
            drawer: false,
            customWidth: 180,
            imagePath: downloadImage,
        };
    },
    methods: {
        toggleDrawer() {
            // Toggle the 'drawer' variable
            this.drawer = !this.drawer;
        },
    },
};
</script>

<style scoped>
.borderr {
    border-radius: 70px !important;
}

.list-item {
    margin-bottom: 10px;
    /* Adjust the margin to control the spacing */
}

.cardcolor {
    background-color: #0f1724;
    color: white;
}

.img-fluid {
    max-width: 70%;
    height: auto;
}
</style>
