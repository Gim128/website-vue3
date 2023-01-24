<template>
    <div class="text-center">
        <v-menu offset-y>
          <template v-slot:activator="{ on, attrs }">
            <v-btn
              color="white"
              dark
              v-bind="attrs"
              v-on="on"
              class="px-2 py-5 text-white cursor-pointer hover:text-yellow-500"
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

<script>
    export default {
    name: "ButtonComponent",
        
    data: () => ({
      items: [
        { title: 'English' },
        { title: 'China' },
      ],
    }),
  }
</script>

<style scoped>

</style>