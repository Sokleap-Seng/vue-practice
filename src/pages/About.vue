<template>
    <section class="bg-gray-100 lg:px-8 mt-4">
        <div class="p-6">
            <h1 class="font-bold text-4xl text-gray-800 mb-2">Fruit</h1>
            <p class="text-gray-600 mb-6">Lorem ipsum dolor sit amet, consectetur adipisicing elit. Sapiente qui est doloribus eligendi nulla consequatur molestias non deleniti. Ad perferendis fuga cum rerum harum omnis nostrum cupiditate iusto sed officia.</p>

            <div class="grid grid-cols-1 sm:grid-cols-2 md:grid-cols-3 lg:grid-cols-4 gap-6">
                <!-- Fruit Cards -->
                <div v-for="(fruit, index) in fruits" :key="index" class="bg-white rounded-2xl shadow-md hover:shadow-xl transition-shadow duration-300 flex flex-col items-center p-4">
                    <img :src="fruit.image" :alt="fruit.name" class="w-32 h-32 object-contain mb-3" />
                    <p class="font-semibold text-lg text-gray-800">{{ fruit.name }}</p>
                </div>
            </div>
        </div>
    </section>
</template>

<script>
export default {
  data() {
    return {
      fruits: [
        { name: "Orange", image: "../src/assets/images/Orange.png" },
        { name: "Apple", image: "../src/assets/images/apple.png" },
        { name: "Mango", image: "../src/assets/images/mango.png" },
        { name: "Pomegranate", image: "../src/assets/images/Pomegranate.png" },
        { name: "Strawberry", image: "../src/assets/images/Strawberry.png" },
        { name: "Starfruit", image: "../src/assets/images/mango.png" },
        { name: "Litchi", image: "../src/assets/images/litchi png.png" },
        { name: "Persimmon", image: "../src/assets/images/persimmon.png" },
      ],
    };
  },
};
</script>

<style scoped>

</style>
