<template>
    <v-form>
        <v-container>
            <v-layout row wrap>
                <v-flex xs12 sm6 md3>
                    <v-text-field label="Driver ID"></v-text-field>
                </v-flex>
            </v-layout>
            <v-layout row wrap>
                <v-flex xs12 sm6 md3>
                    <v-text-field label="Driver name"></v-text-field>
                </v-flex>
            </v-layout>
            <v-layout>
                <v-checkbox label="Water"></v-checkbox>
            </v-layout>
            <v-layout>
                <v-checkbox label="Oil"></v-checkbox>
            </v-layout>
            <v-layout row wrap>
                <v-flex xs12 sm6 md3>
                    <v-text-field label="Tire Pressure"></v-text-field>
                </v-flex>
            </v-layout>
        </v-container>
    </v-form>
</template>

<script>
export default {
    
}
</script>
