<template>
    <div class="text-center">
      <v-container>
        <v-row justify="center">
          <v-col cols="10">
            <v-container class="max-width">
              <v-pagination
                v-model="page"
                :page-count="pageCount"
                :length="15"
                :total-visible="4"
                class="my-4"
              ></v-pagination>
            </v-container>
          </v-col>
        </v-row>
      </v-container>
    </div>
  </template>
  
  <script>
    export default {
      data() {
        return {
          page: 1,
        }
      },
    }
  </script>
  