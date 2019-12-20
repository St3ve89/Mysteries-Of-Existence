<template>
    <v-container fluid>
        <v-layout wrap class="mt-5" justify-start>
            <v-flex xs9 sm8 md5 lg3 xl3>
                    <v-card
                        class="mt-3 mb-3"
                        min-width="100"
                        max-width="250px"
                        v-for="n in 2"
                        :key="n"
                    >
                    <v-img
                    class="white--text align-end"
                    height="200px"
                    src="https://cdn.vuetifyjs.com/images/cards/docks.jpg"
                    >
                    <v-card-title>Top 10 Australian beaches</v-card-title>
                    </v-img>
                    <v-card-subtitle class="pb-0">Number 10</v-card-subtitle>

                    <v-card-text class="text--primary">
                    <div>Whitehaven Beach</div>

                    <div>Whitsunday Island, Whitsunday Islands</div>
                    </v-card-text>

                    <v-card-actions>
                    <v-btn
                        color="orange"
                        text
                    >
                        Read More
                    </v-btn>
                    </v-card-actions>
                </v-card>
            </v-flex>
            <v-flex xs9 sm8 md5 lg3 xl3>
                <v-card
                        class="mt-3 mb-3"
                        min-width="100"
                        max-width="250px"
                        v-for="n in 2"
                        :key="n"
                    >
                    <v-img
                    class="white--text align-end"
                    height="200px"
                    src="https://cdn.vuetifyjs.com/images/cards/docks.jpg"
                    >
                    <v-card-title>Top 10 Australian beaches</v-card-title>
                    </v-img>
                    <v-card-subtitle class="pb-0">Number 10</v-card-subtitle>

                    <v-card-text class="text--primary">
                    <div>Whitehaven Beach</div>

                    <div>Whitsunday Island, Whitsunday Islands</div>
                    </v-card-text>

                    <v-card-actions>
                    <v-btn
                        color="orange"
                        text
                    >
                        Read More
                    </v-btn>
                    </v-card-actions>
                </v-card>
            </v-flex>
            <v-flex md5 lg6 xl6>
                <h1>Welcome to Mysteries of Existence</h1>
                <p class="mt-2">
                    Mysteries of Existence is a Platform dedicated to people who question today's reality and paradgims.
                    It is a place for likeminded individuals to meet, chat, and exchange ideas as we explore this place that
                    we currently call home.
                </p>
                <p>
                    Here we attempt to shed some light on current events, numerology, astrology and it's relation 
                    to our planet and it's history. A lot of the work you see here has taken inspiration from
                    prominent figueres all across the world who are currently exploring these fields. 
                </p>
                <p>
                    Another important topic which we will be exploring on this platform is the idea that we 
                    were once a much more advanced civilization, evidence for this is spread all across the world,
                    and can be especially seen in the pyramids and their construction which can not be replicated
                    even with today's tools.
                </p>
                <p>
                    Some of these figueres are:
                </p>
                <ul>
                    <li>Graham Hancock</li>
                    <li>Randall Carlson</li>
                    <li>Elon Musk</li>
                    <li>Nick Hinton</li>
                    <li>Bob Lazar</li>
                    <li>Jeremy Kenyon Lockyer Corbell</li>
                    <li>The Randonaut Society & Their Telegram Randomizer Bot</li>
                </ul>
                <p class="mt-5">
                    Some of the ancient civilizations which we will be exploring are:
                </p>
                <ul>
                    <li>Mayan</li>
                    <li>Egyptian</li>
                    <li>Ancient Chinese & Asain civilizations</li>
                    <li>Lost civilizations that we can see are udner water</li>
                </ul>
            </v-flex>
        </v-layout>
    </v-container>
</template>

<script>
export default {
    
}
</script>

<style scoped>

</style>